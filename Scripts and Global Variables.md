# Scripts and Global Variables

## 

### Included Expanders

- [UUID](#uuid)
- [Header](#header)
- [Comment with date](#comment-with-date)
- [IP](#ip)
- [Switch case](#switch-case)
- [Repeater](#repeater)

### UUID

Description:

` uuid`

will render:


```
 uuid() {
     
 }
```



### Header

Description:

> Header available within any editor

` head test.swift`

will render:


```swift
 //
 //  test.swift
 //
 //  Created by Dustin Knopoff on 18/10/2018.
 //  Copyright © 2018 Undefined Variable. All rights reserved.
 //
```

Languages: ['swift']



### Comment with date

Description:

` dc Sample comment`

will render:


```
 // [2018-10-18 09:34:22] Sample comment
```



### IP

Description:

` ip`

will render:


```
 ip() {
     
 }
```



### Switch case

Description:

` en hello aa,bb,cc`

will render:


```
 enum hello {
     case aa
     case bb
     case cc
 }
```



### Repeater

Description:

` rp 1 7 you are on card {} of 27`

will render:


```
 <rp>1 7 you are on card {} of 27</rp>
```



