# 24012011225_MAD_8
# Hello World iOS App using SwiftUI

## 🎯 Aim
To create a basic **Hello World iOS application** using SwiftUI in Xcode.

## 📖 Description
This project demonstrates the development of a simple iOS application using SwiftUI, Apple's modern framework for building user interfaces across Apple platforms. The application displays a "Hello, World!" message on the screen.

## 🛠️ Technologies Used
- **Language:** Swift
- **Framework:** SwiftUI
- **IDE:** Xcode
- **Platform:** iOS

## ✨ Features
- Simple and clean user interface.
- Displays the message "Hello, World!"
- Uses SwiftUI declarative syntax.
- Demonstrates the basic structure of an iOS application.

## 💻 Source Code

```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        VStack {
            Text("Hello, World!")
                .font(.largeTitle)
                .fontWeight(.bold)
                .padding()
        }
    }
}

#Preview {
    ContentView()
}
```

## 🚀 How to Run
1. Open Xcode on your Mac.
2. Create a new iOS project.
3. Select **App** as the project template.
4. Choose **SwiftUI** for the interface and **Swift** for the language.
5. Open `ContentView.swift`.
6. Replace the existing code with the source code provided above.
7. Select an iOS Simulator or connect a compatible iPhone.
8. Click the **Run (▶)** button to build and launch the application.

## 📱 Expected Output
The application displays the following message in the center of the screen:

**Hello, World!**

## 📚 Learning Outcomes
- Understand the basic structure of a SwiftUI application.
- Learn how to use the `Text` view.
- Understand the use of `VStack` for arranging views vertically.
- Learn how to run an iOS application using Xcode.

## 👨‍💻 Developed By
Manish Singh

## 📄 License
This project is created for educational and practical assignment purposes.
