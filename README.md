# BLE-UART-Project
Projeto BLE-UART de Sistemas Embarcados solicitado pelo professor Erick Barboza do IC-UFAL. O projeto implementa a comunicação entre uma central e um periférico utilizando a tecnologia Bluetooth Low Energy (BLE) e o protocolo UART (Universal Asynchronous Receiver/Transmitter). Na comunicação, a central envia uma string para o periférico, que converte a string para letras maiúsculas e retorna o resultado para a central.

Alunos: Matheus Vieira Faria, Rangel Gonçalves, Daniel Pessoa Máximo e Ana Maria Cardoso Wagner.

# Comando para ativação no Renode
Após entrar no terminal do renode basta digitar o seguinte comando:

s @scripts/single-node/nrf52840-ble-zephyr.resc

Certifique-se que o arquivo 'nrf52840-ble-zephyr.resc' esteja dentro da pasta scripts do renode.
