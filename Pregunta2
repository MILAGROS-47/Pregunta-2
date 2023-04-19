class CuentaBancaria{
    constructor(numeroCuenta, saldoInicial){
        this.numeroCuenta=numeroCuenta;
        this.saldo=saldoInicial;
    }
    depositar(cantidad){
        this.saldo+=cantidad;
        console.log(`Se depositaron S/.${cantidad}. El saldo actual de la cuenta es S/.${this.saldo}.`);
    }
    retirar(cantidad){
        if(cantidad <= this.saldo){
            this.saldo-=cantidad;
            console.log(`Se retiraron S/.${cantidad}. El saldo actual de la cuenta es S/.${this.saldo}`);    
        }else{
            console.log(`No se puede retirar S/.${cantidad}. El saldo actual de cuenta es S/.${this.saldo}`);
        }
    }
}

const miCuenta = new CuentaBancaria("123456789", 100);
miCuenta.depositar(50);
miCuenta.retirar(30);
miCuenta.retirar(200);
