## Backappx-Package

<BR>
BackAppX-Gradle is a Kotlin Gradle library for the BackAppX platform.

Getting started
This package is currently under development. Please use it at your own risk.

Features
The library provides a simple way to integrate the BackAppX platform into your Kotlin app.
It provides the following classes:

Auth: this class provides a simple way to authenticate clients with the BackAppX platform.
Product: this class provides a simple way to manage products from the BackAppX platform.
Category: this class provides a simple way to manage categories from the BackAppX platform.
Order: this class provides a simple way to manage orders from the BackAppX platform.
Payment: this class provides a simple way to manage payments from the BackAppX platform using the Stripe API.
FileStorage: this class provides a simple way to manage project's files from the BackAppX platform.
Project: this class provides a simple way to link user's project to the BackAppX platform.
Installation
Add the following dependency to your build.gradle.kts file:

```kotlin
dependencies {
    implementation("com.backappx:backappx:1.0.0")
}
```

## Requirements
The package requires the following dependencies: <br>




## Usage
To use this package, add backappx as a dependency in your Kotlin file.

```Kotlin

import com.backappx.BackAppX

// Your code here


```

## License

MIT License

Copyright (c) 2023 BackAppX

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Additional information

For help getting started with Flutter, view our online [documentation](https://back-app-x-documentation.vercel.app/).
