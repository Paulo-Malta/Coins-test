var n1 = Number(window.prompt("Digite seu Salario"))

 var n2 = window.prompt("Em que moeda você deseja ver seu salario")

 if (n2 === "dolar") {
    document.write("<p>Seu salário em dólares é: " + n1.toLocaleString('en-US', { style: 'currency', currency: 'USD' }) + "</p>");
} 

else if (n2 === "Dolar") {
    document.write("<p>Seu salário em reais é: " + n1.toLocaleString('pt-BR', { style: 'currency', currency: 'USD' }) + "</p>");
} 



else if (n2 === "real") {
    document.write("<p>Seu salário em reais é: " + n1.toLocaleString('pt-BR', { style: 'currency', currency: 'BRL' }) + "</p>");
} 

else if (n2 === "Real") {
    document.write("<p>Seu salário em reais é: " + n1.toLocaleString('pt-BR', { style: 'currency', currency: 'BRL' }) + "</p>");
} 




else if (n2 === "euro") {
    document.write("<p>Seu salário em euros é: " + n1.toLocaleString('de-DE', { style: 'currency', currency: 'EUR' }) + "</p>");
} 

else if (n2 === "Euro") {
    document.write("<p>Seu salário em euros é: " + n1.toLocaleString('de-DE', { style: 'currency', currency: 'EUR' }) + "</p>");
} 



else {
    window.alert("Moeda não reconhecida.");
}
