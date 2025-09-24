# MQTT_ESP32
Repositório do projeto de IoT. O dispositivo (Norvi GSM AE04-i) possui uma ESP32, o objetivo é captar dados de campo e mandar para um dashboard por meio de mqtt. Além disso os dados são tratados e armazenados em um BD (MySQL)
<br>
<strong>

  ### Pastas
  
</strong>
<br>
<p>
  O projeto está armazenado na branch Master e organizado da seguinte forma: <br>
  ESP32 <br>
    - Manuais Norvi GSM AE04-i <br>
    - Node-Red <br>
    - src <br>
</p>
<em>
  
### Monitoramento

</em>
<br>
O Node-Red é uma ferramenta para criação de fluxos visuais, ela permite tratar dados e integrar ferramentas e sistemas para trocarem informações entre si.
No caso desse projeto o Node-Red foi usado para consumir dados de um tópico MQTT, exibir um dashboard em tempo real com gráficos e indicadores importantes referentes ao processo.
<br>

## Fluxo visual 

<img width="1248" height="792" alt="image" src="https://github.com/user-attachments/assets/5d5d6a7a-e0ef-49e0-95c5-80824f0d3388" />


## Armazenamento
  <p>
    Os dados são captados por um nó MQTTIN e então tratados por Function e armazenados em um BD. O banco de dados está rodando localmente com uso do Docker, para virtualizar um servidor.
  </p>
  <br>
  
### Fluxo Armazenamento
  
<img width="818" height="299" alt="image" src="https://github.com/user-attachments/assets/53475562-2bf6-493e-94cc-5ecf0314ac2a" />

### Container Docker

<img width="1224" height="517" alt="image" src="https://github.com/user-attachments/assets/236cd221-b4fa-48a8-a8c0-0317766da401" />

### Querys

<img width="455" height="872" alt="image" src="https://github.com/user-attachments/assets/62845184-9323-4b4b-9be4-ce1cf6a424a4" />



