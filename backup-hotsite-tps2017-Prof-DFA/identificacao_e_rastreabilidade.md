## Identificação e rastreabilidade dos arquivos de log das urnas eletrônicas anteriores ao modelo UE2020

A identificação individual das urnas eletrônicas e a vinculação de seus registros de funcionamento são os pontos centrais do argumento apresentado. 
Cada urna possui um log, isto é, um arquivo que registra os acontecimentos durante sua operação, além de um código de identificação próprio, comparado a um “CPF” do equipamento. 
Para estabelecer a correspondência entre o histórico e a urna que o gerou, esse registro deve estar associado à identificação da respectiva máquina.
Nos modelos anteriores à UE2020, um mesmo código aparece nos logs de aproximadamente 250 mil urnas, em vez de individualizar cada equipamento.
Se não há individualização de cada urna, não há como comprovar que aquele log (histórico) é daquela urna específica.

Como apontado no relatorio do PL , de fato  há um problema nos logs das máquinas antigas, o campo ID_UE está mostrando o número 67305985 (0x01020304, uint32le), provavelmente um valor padrão não inicializado , coomo no emplo da imagem  abaixo

<br>


<img width="1114" height="848" alt="445746654-e8cb67ae-0819-48e7-bf20-6f36252a4158" src="https://github.com/user-attachments/assets/a07231f0-2aa8-40ad-8ed5-aa9878c594b5" />


<br><br>


## Exemplo  de  urna que travou e foi desligada.

<br>

<img width="1015" height="278" alt="exemplo_urna_travada_desligada" src="https://github.com/user-attachments/assets/f67841bf-ee6a-43fc-96b8-ae1950cea88a" />
