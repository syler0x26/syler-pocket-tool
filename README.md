# syler-pocket-tool

>  **Status: Em planejamento**, ainda na fase de pesquisa e definição de peças, nenhum hardware montado ainda.

Dispositivo portátil inspirado no Flipper Zero, baseado em ESP32, com o objetivo de escanear redes Wi-Fi/BLE e capturar sinais sub-GHz e infravermelho para posterior reprodução.

---

##  Objetivo

- Escanear redes Wi-Fi e dispositivos Bluetooth/BLE próximos
- Capturar sinais sub-GHz (433/868 MHz) de código fixo e retransmiti-los
- Capturar e reproduzir sinais de infravermelho (controles remotos)
- Guardar os sinais capturados para uso posterior

##  Peças planejadas

| Função | Componente |
|---|---|
| Processamento + Wi-Fi/BLE | ESP32 |
| Sub-GHz | CC1101 |
| Infravermelho | LED IR + receptor TSOP |
| Interface | Tela OLED/TFT + botões |
| Alimentação | Bateria LiPo + módulo de carregamento |

##  Stack planejada

- Firmware em C++ (Arduino/PlatformIO)
- Bibliotecas: `RadioLib` ou `ELECHOUSE_CC1101`, `IRremoteESP8266`

## Roadmap

- [ ] Definir lista final de peças
- [ ] Montar protótipo com ESP32 + OLED (scan Wi-Fi/BLE)
- [ ] Adicionar módulo CC1101 (sub-GHz)
- [ ] Adicionar módulo IR
- [ ] Implementar armazenamento dos sinais capturados
- [ ] Montar case/carcaça

## ⚠️ Aviso

Projeto com fins educacionais. Uso previsto apenas em dispositivos e redes próprias ou com autorização explícita.
