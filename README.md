# SPStorkController
Modal controller as in mail or Apple music application. Similar animation and transition. Now in develop

Preview GIF loading `4mb`. Please, wait

<img src="https://rawcdn.githack.com/IvanVorobei/RequestPermission/fb53d20f152a3e76e053e6af529306611fb794f0/resources/request-permission - mockup_preview.gif" width="500">

<img src="https://rawcdn.githack.com/IvanVorobei/RequestPermission/6fcd9bdb50a99cea358294999e161dffe55be46f/resources/request-permission - donate.svg"/>

The project is absolutely free, but but it takes time to support and update it. Your support is very motivating and very important. I often receive emails asking me to update or add functionality. [Small donate](https://money.yandex.ru/to/410012745748312) for a cup of coffee helps to develop the project and make it better

<img src="https://rawcdn.githack.com/IvanVorobei/RequestPermission/6fcd9bdb50a99cea358294999e161dffe55be46f/resources/request-permission - donate.svg"/>

## Requirements
Swift 4.2. Ready for use on iOS 10+

## Integration
Drop in `source/sparrow` folder to your Xcode project. Make sure to enable `Copy items if needed` and `Create groups`

Or via CocoaPods:
```ruby
pod 'SPStorkController'
```

and import library in class:
```swift
import SparrowKit
```

## How to use
Init controller (please, set background, it maybe clear color) and set `transitioningDelegate`. Use `present` or `dissmiss` funcs:
```swift
import SparrowKit

let controller = UIViewController()
let transitionDelegate = SPStorkTransitioningDelegate()
controller.transitioningDelegate = transitionDelegate
controller.modalPresentationStyle = .custom
present(controller, animated: true, completion: nil)
```

## License
`SPStorkController` is released under the MIT license. Check LICENSE.md for details

## Contact
If you need develop application or UI, write me to hello@ivanvorobei.by. I am develop design and ios apps. I am use `swift`. If you want to ask for more functionality, you should create a new issue

[hello.ivanvorobei.by](https://hello.ivanvorobei.by) & [ivanvorobei.by](https://hello.ivanvorobei.by) 

My apps [in AppStore](https://itunes.apple.com/us/developer/polina-zubarik/id1434528595) & [in AppStore 2](https://itunes.apple.com/us/developer/mikalai-varabei/id1435792103)