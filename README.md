https://www.codewars.com/kata/string-scramble/train/javascript


function scramble(str, arr) {
let newArr = [];
str = str.slice(',');
 for(let i = 0, j = 0; i < str.length, j < arr.length; i++, j++){
      newArr.push(str[arr.indexOf(i)]);
    }
    let a = newArr.join('');
    return a;
};



