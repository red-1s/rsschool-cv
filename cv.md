# Denis Murlatovskiy

## Contacts

* **Telegram:** [red_1s](https://t.me/red_1s)
* **Email:** [yarkay.rabota@gmail.com](mailto:yarkay.rabota@gmail.com)
* **Github:** [red-1s](https://github.com/red-1s)
* **Discord:** [red.1s](https://discordapp.com/users/red.1s/)


## About me

I am 30 years old and am an iOS developer with more than 5 years of experience in 7 projects. My key goal today is to develop my skills and master new technologies. First of all, I see mobile development as a priority area for myself, but I also strive to broaden my horizons in the frontend. I see perseverance in solving problems of any complexity as my main feature.

## Key skills

* Swift, Objective-C
* Xcode
* UIKit, CocoaPods
* Swift UI, CoreData, Combine
* UI Testing
* MVC, MVVM
* Git Flow
* REST API

## Code Examples
```
private func truncateNames(_ text: String?, width: CGFloat) -> String {
    let namesLabelHorizontalPaddings: CGFloat = 56
    guard var text = text, width >= namesLabelHorizontalPaddings else { return "" }
    let separator = ","
    var names = text.components(separatedBy: separator)
    text = names.joined(separator: separator)
    if widthForView(text: text) > (width - namesLabelHorizontalPaddings) {
        names.removeLast()
        return truncateNames(names.joined(separator: separator), width: width)
    }
    return text
}

private func widthForView(text: String) -> CGFloat {
    let font = UIFont.systemFont(ofSize: 12)
    let namesLabelHeight: CGFloat = 16
    let label = UILabel(frame: CGRect(x: 0, y: 0, width: CGFloat.greatestFiniteMagnitude, height: namesLabelHeight))
    label.numberOfLines = 1
    label.lineBreakMode = NSLineBreakMode.byWordWrapping
    label.font = font
    label.text = text
    label.sizeToFit()
    return label.frame.width
}
```

## Experience

* **OOO Litres 07.19 - 02.22** — [[more]](https://www.litres.ru/o-kompanii/)
	* [Litres: Books and Audiobooks](https://apps.apple.com/ru/app/литрес-книги-и-аудиокниги/id438441429)
	* [Books and audiobooks MyBook](https://apps.apple.com/ru/app/книги-и-аудиокниги-mybook/id556540446)
	* Comics Time

* **Transcapital Bank 06.17 - 07.19** — [[more]](https://www.tkbbank.ru/bank/about/)
	* TCB Express Online Bank
	* TCB Transfers
	* TCB Key

* **Cloud technologies 02.16 - 06.17**
	* Development of corporate CRM systems

* **Wawe Idustries LLC 09.14 - 12.15** — [[more]](wawe.me)
	* Social Network Wawe 

## Education

* **MATI — Russian State Technological University 2009 - 2014**
	* Information systems and technologies, Automated information processing and management systems
	* Military Department
	
* **Specialist Training Center at Bauman Moscow State Technical University, Objective-C 2.0**
	* Programming in C family languages

## Languages

* Russian — native
* English — B1
 
----