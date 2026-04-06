
const animals = {
"גאקו": {
category: "תוכים",
price: "3500-6000 ₪",
info: "תוכי חכם מאוד שצריך יחס, משחקים ותזונה מגוונת."
},
"קוקטייל": {
category: "תוכים",
price: "400-800 ₪",
info: "תוכי קטן וחברותי שקל יחסית לגדל."
},
"ארנב": {
category: "מכרסמים",
price: "100-300 ₪",
info: "צריך חציר, ירקות וכלוב גדול."
},
"אוגר": {
category: "מכרסמים",
price: "30-80 ₪",
info: "פעיל בעיקר בלילה ואוהב גלגל ריצה."
},
"איגואנה": {
category: "זוחלים",
price: "500-1200 ₪",
info: "צריכה מנורת חימום ותאורה מיוחדת."
},
"דג זהב": {
category: "דגים",
price: "5-20 ₪",
info: "צריך אקווריום עם פילטר."
},
"כלב": {
category: "יונקים",
price: "1000-5000 ₪",
info: "צריך טיולים, חיסונים ואוכל איכותי."
},
"חתול": {
category: "יונקים",
price: "300-1500 ₪",
info: "צריך ארגז חול וטיפול וטרינרי."
}
};

function searchAnimal(){

let name = document.getElementById("searchBox").value;
let result = document.getElementById("result");

if(animals[name]){

let a = animals[name];

result.innerHTML =
"<b>קטגוריה:</b> " + a.category +
"<br><b>מחיר:</b> " + a.price +
"<br><b>מידע:</b> " + a.info;

}else{

result.innerHTML = "החיה לא נמצאה במערכת";

}

}
