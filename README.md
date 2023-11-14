<h1 align="center">TechPro</h1>

```javascript
(function (document) {
    var checkCount = 0,
      formatFound = false;
  
    function setHTMLClass(height, className) {
      checkCount++;
      if (height == 2) {
        formatFound = true;
        document.documentElement.className += " " + className;
      } else {
        document.documentElement.className += " not" + className;
        if (checkCount == 4 && !formatFound) {
          if (
            document.implementation.hasFeature(
              "http://www.w3.org/TR/SVG11/feature#Image",
              "1.1"
            )
          ) {
            document.documentElement.className += " svg";
          } else {
            document.documentElement.className += " notsvg png";
          }
        }
      }
    }
  
    var JXL = new Image();
    JXL.onload = JXL.onerror = function () {
      setHTMLClass(JXL.height, "jxl");
    };
    JXL.src =
      "data:image/jxl;base64,/woIELASCAgQAFwASxLFgkWAHL0xqnCBCV0qDp901Te/5QM=";
  
    var AVIF = new Image();
    AVIF.onload = AVIF.onerror = function () {
      setHTMLClass(AVIF.height, "avif");
    };
    AVIF.src =
      "data:image/avif;base64,AAAAIGZ0eXBhdmlmAAAAAGF2aWZtaWYxbWlhZk1BMUIAAADybWV0YQAAAAAAAAAoaGRscgAAAAAAAAAAcGljdAAAAAAAAAAAAAAAAGxpYmF2aWYAAAAADnBpdG0AAAAAAAEAAAAeaWxvYwAAAABEAAABAAEAAAABAAABGgAAAB0AAAAoaWluZgAAAAAAAQAAABppbmZlAgAAAAABAABhdjAxQ29sb3IAAAAAamlwcnAAAABLaXBjbwAAABRpc3BlAAAAAAAAAAIAAAACAAAAEHBpeGkAAAAAAwgICAAAAAxhdjFDgQ0MAAAAABNjb2xybmNseAACAAIAAYAAAAAXaXBtYQAAAAAAAAABAAEEAQKDBAAAACVtZGF0EgAKCBgANogQEAwgMg8f8D///8WfhwB8+ErK42A=";
  
    var WebP = new Image();
    WebP.onload = WebP.onerror = function () {
      setHTMLClass(WebP.height, "webp");
    };
    WebP.src =
      "data:image/webp;base64,UklGRjoAAABXRUJQVlA4IC4AAACyAgCdASoCAAIALmk0mk0iIiIiIgBoSygABc6WWgAA/veff/0PP8bA//LwYAAA";
  
    var JPX = new Image();
    JPX.onload = JPX.onerror = function () {
      setHTMLClass(JPX.height, "jpx");
    };
    JPX.src =
      "data:image/vnd.ms-photo;base64,SUm8AQgAAAAFAAG8AQAQAAAASgAAAIC8BAABAAAAAQAAAIG8BAABAAAAAgAAAMC8BAABAAAAWgAAAMG8BAABAAAARgAAAAAAAAAkw91vA07+S7GFPXd2jckQV01QSE9UTwAZAMFxAAAAATAAoAAKAACgAAAQgCAIAAAEb/8AAQAAAQDCPwCAAAAAAAAAAAAAAAAAjkI/AIAAAAAAAAABIAA=";
  
    var JP2 = new Image();
    JP2.onload = JP2.onerror = function () {
      setHTMLClass(JP2.height, "jp2");
    };
    JP2.src =
      "data:image/jp2;base64,/0//UQAyAAAAAAABAAAAAgAAAAAAAAAAAAAABAAAAAQAAAAAAAAAAAAEBwEBBwEBBwEBBwEB/1IADAAAAAEAAAQEAAH/XAAEQED/ZAAlAAFDcmVhdGVkIGJ5IE9wZW5KUEVHIHZlcnNpb24gMi4wLjD/kAAKAAAAAABYAAH/UwAJAQAABAQAAf9dAAUBQED/UwAJAgAABAQAAf9dAAUCQED/UwAJAwAABAQAAf9dAAUDQED/k8+kEAGvz6QQAa/PpBABr994EAk//9k=";
  })(
    (window.sandboxApi &&
      window.sandboxApi.parentWindow &&
      window.sandboxApi.parentWindow.document) ||
      document
  );
```

## About the project
<table width="100%">
    <tbody width="100%">
        <tr>
            <td rowspan=5 align="rigth">
                <img src="https://github.com/marcosguz/hearing/assets/75583218/5dfa18b4-958b-40ea-bdac-581b581bec75" width="500px">
            </td>
        </tr>
        <tr>
            <td align="justify">This web application is developed for educational purposes to implement preprocessor code.</td>
        </tr>
        <tr>
            <td align="justify">
				<a href="https://techpro-store.netlify.app/">TechPro</a>
			</td>
        </tr>
    </tbody>
</table>

## Developed with
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SASS Badge](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)

## How to contribute?
Contributions are what make the open source community an amazing place to learn, inspire, and create. Any contribution you make is greatly appreciated.

1. Fork the project.
2. Create a feature branch: (git checkout -b features/amazing-feature).
3. Commit your changes: (git commit -m 'Add an Amazing Feature').
4. Upload your changes to the branch: (features/amazing-feature)
5. Open a pull request

## License
Distributed under the MIT license. See the `LICENSE` file for more information.

## Contact
Marcos Guzmán

<a href="https://www.linkedin.com/in/marcos-guzman-nazareno" target="blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Marcos"/>
</a>
<a href="https://twitter.com/marccosgz" target="blank">
      <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
</a>

## Recognitions
- [Sass](https://github.com/sass/sass)
- [Marked](https://marked.js.org/)
