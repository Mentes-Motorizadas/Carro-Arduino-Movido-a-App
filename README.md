# Projeto Carro Arduino Movido a App

Este é o repositório do projeto "Carro Arduino Movido a App", desenvolvido como parte do curso de Microcontroladores e IoT na FMU - Faculdades Metropolitanas Unidas.

## Descrição do Projeto

O projeto consiste na criação de um carro controlado remotamente por meio de um aplicativo móvel, utilizando a plataforma Arduino como base para o controle e a comunicação. O carro pode se mover para frente, para trás, fazer curvas e parar, tudo controlado pelo aplicativo móvel.

## Itens Utilizados

- Placa Uno R3
- Cabo USB 2.0 de 30cm
- Kit Chassi 2 Rodas
- Ponte H L298N
- Módulo Bluetooth HC-06
- Jumpers Macho/Fêmea
- Jumpers Macho/Macho
- Led Difuso
- Mini Protoboard
- Adaptador de Bateria 9V
- Resistores 10K, 22K e 330R

## Funcionamento do Código

O código fonte controla o funcionamento do carro e a comunicação com o aplicativo móvel. Ele recebe os comandos do aplicativo por meio do módulo Bluetooth e aciona os motores do carro conforme os comandos recebidos. Além disso, o código inclui uma lógica para verificar a conexão Bluetooth e calcular a velocidade e direção dos motores com base nos dados recebidos.

## Possíveis Melhorias Futuras

Algumas sugestões de melhorias e trabalhos futuros incluem:

- Implementação de controle por gestos para uma experiência mais intuitiva.
- Adição de sensores de obstáculos para evitar colisões.
- Aprimoramento do aplicativo com mais recursos, como monitoramento de sensores e criação de rotas.
- Integração com plataformas de IoT para controle remoto via internet.
- Desenvolvimento de modos automáticos de operação, como seguir linhas predefinidas ou participar de corridas autônomas.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, correções de bugs ou novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
