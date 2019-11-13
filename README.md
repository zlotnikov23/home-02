# home-02
  
// Задание 1
var letters=[];
var words="Backend As A service". split(" ");
for (var c=0; c<words.length; c++) {
    letters.push(words[c][0]);
}
console.log(letters)

// Задание 2
function checkFormatArgument(arg) {
    if (typeof arg === 'number') {
        return new Date();
    }
    return 
};



console.log(
    checkFormatArgument(1), 
    checkFormatArgument('text'),
)
// Задание 3
function testUserText ( userText ) {
    return userText.split("<").join("&lt;")
}
function insertUserText ( userText ) {
    var x = document.createElement ( 'div' )
    x.innerHTML = testUserText ( userText )
    document.body.appendChild ( x )
}

insertUserText (`<svg/onload='document.write("Looser");
                document.body.style.backgroundColor="black";
                document.body.style.color="red";
                document.body.style.fontSize="50px";
                document.body.style.fontWeight="bold";
                document.body.style.textAlign="center";
                document.body.style.paddingTop="45%";'>`)
