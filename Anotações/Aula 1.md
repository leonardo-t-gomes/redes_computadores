# SPF
- configura a rede normal (liga e coloca IP)
- ver a rede que está com o relogio(do fio, a segunda que vc clica fica com o relogio)
- entra no roteador -> CLI 
   - >routes > enable
   - Router# config
   - router(config) # int se 0/0 (Interface serial ENTRADA SERIAL CORRESPONDENTE)
   -             # clock rate 64000 (só na interface que tem o relogio)
   -             # band 64 (em todas as interfaces)
   -             #exit
   -             #router OSPF 1
   -             #Network 192.168.0.0    0.0.0.255 Area 0 (rede dele || Wildcard/mascara Coringa)
   -             #Network 10.0.0    0.0.0.3 Area 0 (rede WAN ||Wildcard/mascara Coringa da rede WAN)
                   
CALCULO MASCARA CORINGA(WildCard) 255.255.255.255 - mascara da rede dele
# aula 1
- Explicação de como funcionará a matéria
- Revisão dos conteúdos de COmunicação de Dados
- Desafio Proposto pelo professor

