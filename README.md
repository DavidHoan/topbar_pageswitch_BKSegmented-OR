BKSegmentedViewControllers
==========================
Connect your scenes in storyboard to buttons (Toolbar or any UIControl with IBAction) 
One viewController can display multiple viewController. 
Example show works like Tabbar but you can set it anywhere on the screen.

It makes life of a developer so easy who has to manage many views in one viewController enjoy happy coding.

<p align="left"><img src="http://cl.ly/image/3m1I0k1I1J39/BKSegementedController.png"/></p>

Works On
=======================
Works on iOS 5.0+, Designed for ios 7.0.


Installation
=======================
Just drag n drop `BKSegmentedVCSegue.h`,`BKSegmentedVCSegue.m` files 
and Declare a property in Container/MainViewController in which you want to swap different view controller.
<br/> Create an IBOutlet of an UIView as follows 
`@property (strong, nonatomic) IBOutlet UIView *containerView;`
Ctrl + Drag from UIButton/UIControl to viewController and select custom segue/BKSegmentedVCSegue.

That's it with just two 2 files inclusion and connecting segues, you are up and ready to run your project.


Contributions
=======================
Any contribution is more than welcome! You can contribute through pull requests and issues on GitHub.


Author
=======================
Contact me on my email: mr.bhavya.kothari@gmail.com


LICENSE
=======================
The MIT License (MIT)
 
 Copyright (c) 2014 Bhavya Kothari
 
 Permission is hereby granted, free of charge, to any person obtaining a copy of
 this software and associated documentation files (the "Software"), to deal in
 the Software without restriction, including without limitation the rights to
 use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
 the Software, and to permit persons to whom the Software is furnished to do so,
 subject to the following conditions:
 
 The above copyright notice and this permission notice shall be included in all
 copies or substantial portions of the Software.
 
 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
 FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
 COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
 IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
 CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
