# 💡 Atividade: "Blink" com LED Interno do Arduino

## 🎯 Objetivo
Esta documentação visa registrar a conclusão da **Entrega Parte 1** da atividade proposta, que consiste na instalação da Arduino IDE e na implementação do programa "Blink" utilizando o LED interno da placa Arduino, conforme o roteiro de autoestudos.

O programa deve fazer o LED interno acender, aguardar um tempo $X$, apagar, aguardar um tempo $Y$ e repetir o ciclo, gerando um efeito de luz piscando.

## 🛠️ Pré-requisitos
1.  Instalação da **Arduino IDE** no computador.
2.  Placa Arduino (modelo utilizado: *[Insira o modelo da sua placa, ex: Arduino Uno, Nano, etc.]*).
3.  Cabo USB para conexão da placa ao computador.

## 💻 Código-Fonte (Sketch)

O sketch abaixo foi carregado na placa para realizar a função "Blink". O tempo de acendimento e de espera (delay) foi configurado para **1000 milissegundos (1 segundo)**.

```cpp

void setup() {

  pinMode(LED_BUILTIN, OUTPUT);
}


void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  
  delay(1000);                      // Aguarda 1000 milissegundos (1 segundo)
  digitalWrite(LED_BUILTIN, LOW);   // Desliga o LED (LOW é o nível de voltagem baixo)
  delay(1000);                      // Aguarda 1000 milissegundos (1 segundo)
}
```

## Realização
As seguintes evidências demonstram o código no IDE, a placa conectada e o funcionamento do "Blink".

### 1. Screenshot da IDE e Código
Captura de tela da Arduino IDE mostrando o código completo e a interface de programação.

<img src="assets/codigo.png" alt="Imagem da IDE com o código que faz o led piscar" width="80%" height="80%">

### 2. Fotografia do Arduino Ligado e LED Aceso
Fotografia da placa Arduino conectada ao computador via USB, com o LED interno aceso.

<img src="assets/arduino.jpg" alt="Imagem com o led aceso" width="70%" height="70%">

### 3. Vídeo do Funcionamento 
Vídeo que mostra o loop de piscar do LED interno, demonstrando o funcionamento contínuo e a cadência de 1 segundo (acesso) e 1 segundo (apagado).

[Clique aqui para acessar o video da demonstração.](https://drive.google.com/file/d/1Xbf6qRRu4Z9kcm8As7HFtvOYE3JWcn2H/view?usp=sharing)