  
  let div1 = document.getElementById("div-1")
  let div2 = document.getElementById("div-2")



function makePasswd() {
  let passwd = ''
  let chars = ["A","B","C","D","E","F","G","H","I","J","K","L","M","N","O","P","Q","R","S","T","U","V","W","X","Y","Z","a","b","c","d","e","f","g","h","i","j","k","l","m","n","o","p","q","r","s","t","u","v","w","x","y","z", "0", "1", "2", "3", "4", "5", "6", "7", "8", "9","~","`","!","@","#","$","%","^","&","*","(",")","_","-","+","=","{","[","}","]",",","|",":",";","<",">",".","?",
  "/"];
  for (let i=0; i<15; i++) {
    passwd = passwd + chars[Math.floor(Math.random()*chars.length)]   
  }
  return passwd;
}


function handleclick() {
    div1.textContent = makePasswd()
    div2.textContent = makePasswd()
}
