[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

![](poster.jpg)

### What's new in 1.8.3:
- Support for desktop

<!-- GETTING STARTED -->
## Getting Started
### Adding dependencies
- Add it in your `commonMain.dependencies`
  ```
  implementation("io.github.shadmanadman:kmp-webview:1.8.3")
  ```

### Usage  
```
@Composable
fun KmpWebViewScreen(
    modifier: Modifier? = null,
    url: String? = null,
    htmlContent: String? = null,
    isLoading: ((isLoading: Boolean) -> Unit)? = null,
    onUrlClicked: ((url: String) -> Unit)? = null
)
```
- `isLoading`: Current loading status of the web view
- `onUrlClicked`: If user click's on a link inside your web view you can handel it here. 
   - *Note*: Images(jpg,pngs) and attachment.id are excluded and will be opened inside your current web view.
   - *Note*: If you don't implement this, all links will be opened in your current web view.

<h1 align="center">Any contribution is very satisfying. </h1>
<h2 align="center">Make it easier for everyone</h2>
