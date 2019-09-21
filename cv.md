Junior Frontend Developer CV
# Andrei Chuyanov
## Contacts

* email: achuyanov@gmail.com
* skype: andrei.chuyanov
* mobile: +375297540133

## Summary
I already have some programming knowledge. I want to know more techolodgies and be able to use it.
## Skills
* Windows, Linux, Sun Solaris, FreeBSD
* Programming for different CAD systems (CATScript, VB, Autodesk Intent Language, etc.)
* SVN, Git
* HTML/CSS/JS
* SQL
* XML
## Code example
```js
let getCellRangeFunc = this.getCellRange;
return function(workSheet, range){
    const dataFromExcel = getCellRangeFunc(workSheet, range)
    const dataFromExcelLength = dataFromExcel.length
    let obj = {}
    for (let i = 0; i < dataFromExcelLength; i++) {
        let subArray = dataFromExcel[i]
        if (subArray.length > 1) obj[subArray[0]] = subArray[subArray.length-1]
    }
    return obj;
}
```
## Experience
    Engineering automation projects - 5 years. Work in multilingual environments.
## Education
* Belarusian National Technical University \  Mechanical Engineering Department 2003
* Codecademy courses : Introduction to HTML, Learn CSS, Introduction to JavaScript

## Languages
 * English - B2
 * French - A1
 * Polish - A2
