ReadMe
---

The SlideViewFramework is a three panel slide controller that takes in three view controllers and uses a slide naviagation. 

Add the static library to your project, and initialize the `ContainerViewController` as follows:

	ContainerViewController *containerVC = [[ContainerViewController alloc] initWithBaseViewController:baseVC andFirst:firstVC andSecond:secondVC];
	
and present the view controller. 

The dropshadows on the first and second view controllers can be adjusted by setting the `ContainerViewController` `shadowOpacity`, `shadowOffset` properties. The defaults for those values, if not set, are 0.5, and (-3.0, 0.5), respectively.