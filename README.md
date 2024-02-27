# 100-Days-of-SwiftUI
Daily Updates on the iOS Development course.


I started learning iOS Development with a course given by Paul on "Hacking with Swift". 

Today is Friday 16th February 2024... 

let's see how I finish this.

see you down the road...

*A week has been gone silent here due to an event organised at my place for 4 days, **Resuming from 24 Feb**.*

## DAY 2 - 25 Feb 2024

- Completed tutorials up to Day - 8 (Functions).
- Gave all the tests and scored 10/12 on average.
- Solved up to 5 problems of algorithms and 4 data structures in HackerRank.

## DAY 4 - 27 Feb 2024

- Completed Closures (Day - 9).
- Code snippet for checkpoint 5:
```swift
import Foundation

let luckyNumbers = [7, 4, 38, 21, 16, 15, 12, 33, 31, 49]

func findLuckyNumbers(from: [Int], by opration: (_ data: [Int]) -> Void) {
    opration(from)
}

findLuckyNumbers(from: luckyNumbers) { data in
    
    // filtering all even numbers
    var filteredEvenNumbers = data.filter { $0 % 2 != 0 }
    
    // sorting an array in ascending order
    filteredEvenNumbers.sort()
    
    // creating a label for presentation
    let finalNumbers = filteredEvenNumbers.map { num in
        return "\(String(num)) is a lucky number."
    }

    finalNumbers.forEach { item in
        print(item)
    }
}
```

- Test results for Closures:
  
  ![Test results](https://github.com/sonirudra/100-Days-of-SwiftUI/assets/145532030/b6454db7-4040-4d6d-8b55-5ec7722c683f)

