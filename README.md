# home-02
// Задание 1
буквы var = [];
var words = " Backend As A service " . сплит ( "  " );
for ( var c = 0 ; c < words . length ; c ++ ) {
    буквы . нажать (слова [с] [ 0 ]);
}
консоль . журнал (буквы)

// Задание 2
function  checkFormatArgument ( arg ) {
    if ( typeof arg ===  ' number ' ) {
        вернуть  новую  дату ();
    }
    вернуть 
};



консоль . журнал (
    checkFormatArgument ( 1 ),
    checkFormatArgument ( ' text ' ),
)
// Задание 3
function  testUserText ( userText ) {
    вернуть  userText . разделить ( « < » ). присоединиться ( " & lt; " )
}
function  insertUserText ( userText ) {
    var x =  документ . createElement ( ' div ' )
    х . innerHTML  =  testUserText (userText)
    документ . тело . appendChild (x)
}

insertUserText ( ` <svg / onload = 'document.write (" Looser ");
                document.body.style.backgroundColor = "черный";
                document.body.style.color = "красный";
                document.body.style.fontSize = "50px";
                document.body.style.fontWeight = "жирный шрифт";
                document.body.style.textAlign = "центр";
                document.body.style.paddingTop = "45%"; '> ` )
