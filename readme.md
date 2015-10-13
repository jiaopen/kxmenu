KxMenu is a vertical popup menu for using in iOS applications
===========================================================

### Fork说明

1.增加了背景蒙版
2.将原有@selector修改为block
3.修改样式

=======================================

![sample png](https://github.com/jiaopen/kxmenu/blob/master/screenshot/example.gif "Sample Png")
![sample gif](https://github.com/jiaopen/kxmenu/blob/master/screenshot/example.png "Sample Gif")

### Usage

1. Drop files from KxMenu/Source folder in your project.

Sample code:

	 [KxMenu showMenuInView:self.view
                   fromRect:sender.frame
                  menuItems:@[
                 	[KxMenuItem menuItem:@"Title"
                     	image:[UIImage imageNamed:@"image"]
                    	target:self
                        action:^{
                            [self pushMenuItem:nil];
                        }],
                 ]];


Look at KxMenuExample demo project as sample of using.

### Requirements

at least iOS 5.0 and Xcode 4.5.0

### Feedback

Tweet me — [@kolyvan_ru](http://twitter.com/kolyvan_ru).
