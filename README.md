## 👋 Olá, me chamo Bryan Feiten!

- Atuo há quase 3 anos como Desenvolvedor Mobile.
- Trabalho principalmente com Flutter, mas também já precisei implementar código nativo (Swift e Kotlin) para lidar com funcionalidades de Bluetooth, GPS e SDKs nativos.
- Atuo principalmente com a área mobile, mas também participo ativamente do back-end dos projetos, onde utilizamos tecnologias como NodeJS e Typescript.

### Como não posso compartilhar partes de projetos em andamento, deixarei aqui algumas funcionalidades que fiquei responsábel pela implementação:
- Aplicativo SmartHome, onde atuei inicialmente com a comunicação com o SDK nativo de uma terceira empresa utilizando Swift. Após isso, por conta de limitações do SDK e necessidades do cliente, o projeto migrou totalmente para uma solução prórpia, para lidar com as automações e toda a comunicação com o firmware que o cliente desejava adicionar. Ficando assim com os seguintes protocolos de comunicação:
  - Mqtt (utilizando o IoT Core da AWS).
  - Bluetooth (Utilizando o protocolo de comunicação de baixa energia (Bluetooth Low Energy / BLE)).
  - Restful APIs.
  - Código nativo para Method e Event Channels onde precisamos criar gatilhos com base na localização do usuário.
Também tivemos funcionalidades ainda mais complexas, como o espelhamento de estado entre dispositivos, automações baseadas em estado, clima ou programações do usuário e outras coisas como utilizar a localização da casa do usuário para verificações de permissionamento, compartilhamento, limitações baseadas no timezone da casa e do usuário, etc...

- Desenvolvi um app que dou suporte atualmente para permitir que inspetores da empresa parceira revisem produtos na China e enviem os dados (documentos, imagens, anotações e avaliações). Este app é responsável por lidar com grandes quantias de dados, e trabalha com conceitos de Offline first, visto que algumas localizades não possuem boa conexão com a internet na China. Um dos problemas iniciais que enfrentamos foi de não ter um feedback satisfatório dos usuários, então implementei ferramentas de análise de falhas e monitoramento de performance, afim de solucionar os erros antes mesmo que fossem reportados por mensagem.
- Um dos outros projetos que atuei foi interno, onde tive que implementar Testes de Interface (os famosos Golden Tests) inteiramente em caixa preta, afim de testar atividades de maneira prática e automatizada, importando apenas o projeto e interagindo com a tela conforme esperado.

**Key Stacks**: Flutter, NodeJS, Android, iOS, SQL, Docker, CI/CD, AWS, IoT, Automated Tests, IoT Core.

---

<div>
  <a href="mailto:bryan.felipe.feiten@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank">
  </a>
  <a href="https://www.linkedin.com/in/BryanFeiten" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
  </a>
</div>
