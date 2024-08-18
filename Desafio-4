const num = (Math.floor(Math.random() * 11));
let continuar = true;
let cont = 1;
alert("Bienvenido, este juego se trata de adivinar el número de 0 a 10.\nTienes 3 intentos, ¡SUERTE!.")
while(true){
    let numUsuario = parseInt(prompt("Ingrese un número de 1 a 10"));
    if (numUsuario == num){
        alert(`Felicidades, lo solucionaste en ${cont} ${cont == 1 ? "intento" : "intentos"}`)
        break
    } else{
        if(cont == 3){
            alert(`No acertaste en los 3 intentos, el número era ${num}.`)
            break
        }else{
            cont++
        }
    }
}
