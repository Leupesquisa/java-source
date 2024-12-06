# JEndpoint - Visual Studio Code Extension  

[![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/woozyone.jendpoint?label=Marketplace&logo=visual-studio-code&color=007ACC)](https://marketplace.visualstudio.com/items?itemName=woozyone.jendpoint)  
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/woozyone.jendpoint?label=Downloads&color=green)](https://marketplace.visualstudio.com/items?itemName=woozyone.jendpoint)  
[![Rating](https://img.shields.io/visual-studio-marketplace/r/woozyone.jendpoint?label=Rating&color=yellow)](https://marketplace.visualstudio.com/items?itemName=woozyone.jendpoint)  

**JEndpoint** is a lightweight, easy-to-use Visual Studio Code extension that helps developers quickly test and validate RESTful endpoints in Java projects. With **JEndpoint**, you can effortlessly interact with your backend APIs directly from VS Code, making the testing process faster and more streamlined.

---

## ✨ Features  

- 🚀 **Quick Endpoint Testing**: Test Java RESTful endpoints without leaving VS Code.  
- 🔧 **Customizable Requests**: Configure headers, query parameters, and request bodies with ease.  
- 📜 **View Response Details**: Inspect response status, headers, and body in a clean and intuitive interface.  
- 🌐 **Support for Multiple HTTP Methods**: GET, POST, PUT, DELETE, PATCH, etc.  
- 📄 **Lightweight Design**: Minimal dependencies for optimal performance.  

---

## 🛠️ Installation  

### From Visual Studio Code  
1. Open the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X` on macOS).  
2. Search for **JEndpoint**.  
3. Click **Install**.  

### From the Marketplace  
1. Visit the [JEndpoint Marketplace Page](https://marketplace.visualstudio.com/items?itemName=woozyone.jendpoint).  
2. Click **Install**.  

---

## 🚀 Getting Started  

1. Open a Java project in VS Code.  
2. Launch the **JEndpoint Panel** by pressing `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS) and searching for **JEndpoint: Open Panel**.  
3. Enter the endpoint URL, select the HTTP method, and (optionally) provide headers or a request body.  
4. Hit the **Send** button to see the response.  

---

## 🎨 Example Use Case  

### Testing a Sample Java API:  

```java
@RestController
@RequestMapping("/api")
public class SampleController {
    @GetMapping("/greet")
    public ResponseEntity<String> greet() {
        return ResponseEntity.ok("Hello, JEndpoint!");
    }
}
```
- **Endpoint:** ```http://localhost:8080/api/greet```
- **Method:** ```GET```
- **Expected Response:** ```Hello, JEndpoint!```
Simply input the endpoint URL in JEndpoint, select ```GET```, and click Send to test!

## ⚙️ Configuration
**Custom Request Headers**
- Use the Headers tab to add or modify custom headers, such as Authorization tokens or Content-Type.
  
**Query Parameters**
- Easily append query parameters by specifying them in the Query Parameters field.
## 📈 Why Use JEndpoint?
- **Efficiency:** Save time by testing endpoints directly in your IDE.
- **Focus:** No need to switch between tools like Postman or your browser.
- **Lightweight:** Designed specifically for quick and straightforward endpoint validation.
## 🧰 Requirements
* Visual Studio Code (version 1.70.0 or later).
* Java backend project using REST APIs (e.g., Spring Boot, Jakarta EE, etc.).
## 🛡️ License
This extension is licensed under the MIT License.

## 🌟 Feedback & Contributions
We love feedback! If you encounter issues or have feature requests, feel free to:

## Report them in the GitHub Issues.
Contribute via pull requests on GitHub.
❤️ Special Thanks
To the developer community for inspiring the creation of tools that make coding faster and simpler.

## 🔗 [Download JEndpoint Now](https://marketplace.visualstudio.com/items?itemName=woozyone.jendpoint&ssr=false#overview)
Start testing your Java RESTful APIs with speed and precision.
