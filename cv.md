# Andrei Chuyanov
---
## Contact:

* email: achuyanov@gmail.com
* skype: andrei.chuyanov
* mobile: +375297540133

3. Summary (your goal, wishes, reveal what is important for you, what do you want and why.
Some kind of self-presentation. In case of lack of experience  Junior Developer sells his/her potential, his/her passion and ability to learn fast. You shouldn't think that everybody is going to teach you when you come to the workplace . Rather being a Junior means always
learning new things from everywhere etc.).
4. Skills (e.g. programming languages, frameworks, methodologies, version control, tools etc.)
## Code example:
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
6. Experience (for a Junior Dev it means all kinds of experience: coding tests, projects from courses,
freelance projects - wherever they had the opportunity to demonstrate skills they have.
Also it would be awesome if you add links to source code)
7. Education (including courses, seminars, lectures, online learning)
8. English (elaborate on what kind of practice you had, if any, how long it lasted and so on)
