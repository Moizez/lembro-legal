# Política de Privacidade do Lembrô

**Aplicativo:** Lembrô (`com.damcode.lembro`)
**Última atualização:** 1º de agosto de 2026

---

## Em uma frase

**O que você registra fica no seu celular, e só sai dele se você autorizar.** Não há
cadastro, não há conta, não há servidor nosso com os seus dados. As três situações em que
algo sai do aparelho — salvar uma cópia, enviar um resumo e o acompanhamento por um
responsável — são todas iniciadas e autorizadas por **você**, e estão descritas uma a uma
abaixo.

O resto deste documento detalha isso, porque a lei pede detalhe — mas a frase acima é a
regra inteira.

## Quem é o responsável

Este aplicativo é desenvolvido e mantido por **Carlos Moisés Batista Henrique**, sob o nome
**DamCode**, desenvolvedor pessoa física, no Brasil.

**Canal para qualquer questão de privacidade, inclusive os pedidos previstos na LGPD:**
`moizezhenrique@gmail.com`

Respondemos em até 15 dias, o prazo do artigo 19 da LGPD.

**Sobre o encarregado (DPO):** como agente de tratamento de pequeno porte, e nos termos da
Resolução CD/ANPD nº 2/2022, não há indicação formal de encarregado — mas o canal de comunicação
acima existe, é atendido, e é por ele que qualquer pedido, dúvida ou reclamação deve chegar.

## Que dados o aplicativo guarda, e onde

Tudo abaixo fica **exclusivamente no armazenamento interno do seu celular**, num banco de
dados que só o Lembrô acessa:

| O que | Para quê |
|---|---|
| Nome e detalhe dos seus lembretes | Mostrar na tela e no aviso |
| Horários, dias e repetição | Saber quando avisar |
| Registros ("tomei às 08:12") | Montar o histórico e o acompanhamento |
| Identificador das suas etiquetas NFC e o nome que você deu a elas | Reconhecer o adesivo quando você encosta o celular |
| Suas preferências (som, vibração, avisos já vistos) | Lembrar do que você escolheu |

**Não pedimos e não guardamos:** seu nome, e-mail, telefone, CPF, endereço, data de
nascimento, contatos, fotos, localização, nem qualquer identificador de publicidade.

**Não guardamos valores de saúde.** O Lembrô registra que a tarefa **aconteceu**, nunca o
resultado dela: não há campo para pressão, glicemia, peso ou qualquer medição. Essa é uma
decisão de produto, não uma limitação temporária.

## Dados sensíveis de saúde

A informação de que você usa um determinado medicamento, e em que horários, é **dado pessoal
sensível** pelo artigo 5º, II da LGPD. Por isso o aplicativo foi construído para que esse
dado **não circule**:

- Ele não é transmitido para nós nem para terceiros.
- Ele não é usado para publicidade, perfilamento ou qualquer finalidade comercial. A LGPD
  proíbe expressamente o uso econômico de dado sensível de saúde (art. 11, §4º), e nós
  também não temos interesse nisso: não é assim que este aplicativo se sustenta.
- Ele não é compartilhado com farmácias, planos de saúde, laboratórios ou anunciantes.

**Nós não acessamos esses dados.** Vale ser preciso aqui, porque é fácil escrever bonito e
impreciso: o artigo 5º, X da LGPD define "tratamento" de forma ampla, e a lista inclui
*armazenamento*. Armazenamento existe — **no seu aparelho**. O que não existe é acesso nosso:
não recebemos cópia, não temos como consultar, exportar ou apagar o conteúdo dos seus
lembretes. Quem decide o que registrar e o que apagar é você, no aparelho.

Isso não é detalhe de redação: é o que faz as três situações abaixo — as únicas em que algo
sai do aparelho — serem **disparadas por você**, e não por nós.

## As três vezes em que algo sai do aparelho — e você decide as três

### 1. Salvar uma cópia de segurança

Em Configurações, "Salvar uma cópia" gera um arquivo com os seus lembretes e o seu histórico
e abre a folha de compartilhamento do próprio sistema, para **você** escolher o destino
(Google Drive, e-mail, WhatsApp, outro aplicativo).

- Nós não recebemos esse arquivo e não sabemos para onde ele foi.
- A partir do momento em que você o envia, ele passa a ser regido pela política do serviço
  que você escolheu.
- O arquivo **não é criptografado**, para que você mesmo possa abri-lo e para que continue
  restaurável no futuro. Guarde-o num lugar de sua confiança.

### 2. Enviar um resumo

Na tela Acompanhamento, "Enviar resumo" monta um **texto** com o que aconteceu e abre a mesma
folha do sistema. Você escolhe se manda, e para quem. Nós não vemos o conteúdo nem o
destinatário.

### 3. O acompanhamento por um responsável — opcional, e o único que usa a nuvem

Um filho, parente ou cuidador pode, **com a sua autorização explícita**, acompanhar de longe
se os seus horários foram registrados. É a única função do aplicativo que envia algo pela
internet, e ela **nasce desligada**: só passa a existir depois que você toca em "Autorizar"
na sua tela, vendo o nome de quem pediu.

**O que viaja — e nada além disto:**

| Dado | Exemplo |
|---|---|
| Nome do lembrete | "Losartana" |
| Horário previsto | 08:00 |
| Horário registrado, ou a ausência dele | registrado às 08:12 / não registrado |
| Como foi registrado | pela etiqueta ou pelo botão |
| O dia a que isso se refere | 2026-08-01 |

**O que nunca viaja:** o campo de detalhe e anotações (onde se escreve dosagem), os nomes das
suas etiquetas, suas configurações, sua localização — que o aplicativo nem coleta — e o
histórico anterior à autorização.

**Onde isso fica:** em um banco de dados do **Google Firebase (Firestore)**, contratado por
nós como operador, em servidor localizado em **São Paulo, Brasil** (região
`southamerica-east1`). A identidade dos aparelhos é **anônima**: um código aleatório criado
pelo Firebase, sem nome, e-mail ou telefone — continua não existindo cadastro. O tratamento
feito pelo Google como operador é regido pela política dele:
https://firebase.google.com/support/privacy

**Quem lê:** somente os aparelhos que **você** autorizou, um a um, pelo código de pareamento.
A autorização é verificada pelo servidor a cada leitura — não é promessa do aplicativo, é
regra do banco. Quem acompanha **vê e não mexe**: não pode registrar por você, não pode
editar nada.

**Você fica sabendo:** enquanto alguém acompanha, a tela inicial mostra um selo permanente
com o nome da pessoa. Não existe modo invisível.

**Para desligar:** Configurações → Quem me acompanha → Remover. **Um toque**, sem
confirmação em cascata. O acesso é cortado na hora, o envio para. E o aplicativo **apaga da
nuvem tudo o que já tinha enviado** — retirar o consentimento não deixa rastro para trás.

**Retenção:** cada dia enviado é **apagado depois de 90 dias**. Quem apaga é o próprio
aplicativo, na primeira vez que ele abrir com internet depois do vencimento — não há
servidor nosso rodando sozinho. Consequência honesta: se o aplicativo for desinstalado sem
que você use o Remover, o que já subiu pode permanecer lá; nesse caso, escreva para o
contato no topo e apagamos. O seu histórico completo continua morando só no seu aparelho.

**Base legal:** o seu **consentimento** (LGPD, art. 11, I — dado sensível), colhido de forma
específica e destacada na tela de autorização. Revogá-lo é o botão Remover.

## Avisos (notificações)

Os avisos são gerados **dentro do seu celular**, pelo próprio aplicativo, e agendados no
sistema operacional. Não há servidor de notificação, não há *push* e nenhuma informação sobre
seus lembretes viaja pela internet para que o aviso chegue.

O aplicativo pede permissão de notificação na primeira abertura. Se você recusar, o Lembrô
continua funcionando — apenas não avisa.

## Etiquetas NFC

O adesivo NFC guarda **apenas um endereço com um identificador aleatório** criado pelo
aplicativo (por exemplo, `lembro://t/tag_a1b2c3`). Ele **não contém** o nome do medicamento,
nem nenhum dado seu.

Isso é deliberado: etiqueta NFC pode ser lida por qualquer celular. Como o identificador só
faz sentido dentro do seu aplicativo, quem encostar outro aparelho no seu adesivo não
descobre nada sobre você.

A permissão de NFC no Android é concedida na instalação e serve só para ler e gravar as suas
etiquetas. Não usamos NFC para pagamento nem para identificar você.

## Permissões e para que servem

| Permissão | Para quê |
|---|---|
| NFC | Ler e gravar as suas etiquetas |
| Notificações | Avisar na hora do lembrete |
| Alarme durante economia de energia | Fazer o aviso chegar mesmo com o celular parado |
| Cobrança no aplicativo (*billing*) | Comprar o Lembrô completo pela loja |

Não pedimos localização, câmera, microfone, contatos, armazenamento externo nem telefone.

## Compras

O Lembrô é gratuito e funcional. Há uma versão completa paga, opcional, e uma assinatura
separada para quem acompanha outra pessoa.

**Quem processa o pagamento é a loja de aplicativos** (Google Play ou App Store), que é a
vendedora legal. O Lembrô **não vê, não recebe e não armazena** dados de pagamento: nem
cartão, nem CPF, nem endereço de cobrança. O aplicativo apenas pergunta à loja se existe uma
compra válida associada à sua conta, e recebe "sim" ou "não".

O tratamento dos seus dados de pagamento é regido pela política de privacidade da loja:

- Google Play: https://policies.google.com/privacy
- App Store: https://www.apple.com/legal/privacy/

## Análise de uso, rastreamento e publicidade

**Não existem no Lembrô.** Não usamos ferramentas de analytics, relatório de falhas,
rastreadores, identificadores de publicidade, *pixels* ou SDKs de terceiros com essa
finalidade. Não sabemos quantas vezes você abriu o aplicativo, nem quais lembretes você tem.

**Uma ressalva honesta sobre a cobrança.** Para vender a versão completa, o aplicativo inclui
a biblioteca de cobrança do próprio Google Play. Ela é do Google, e faz diagnóstico próprio
com os servidores dele sobre o funcionamento da compra — algo que acontece em todo aplicativo
que vende pela loja, e que não passa por nós: não recebemos, não vemos e não conseguimos
acessar essas informações. Nada dos seus lembretes ou registros é enviado por esse caminho.
O que o Google faz com esses dados é regido pela política de privacidade dele, ligada acima.

**E sobre o Firebase.** A biblioteca do Firebase, usada pelo acompanhamento, está presente no
aplicativo — mas só conversa com a internet quando existe um pareamento seu. Não incluímos o
Firebase Analytics nem o Crashlytics: do Firebase, usamos exatamente dois serviços, o banco
do espelho (Firestore) e a identidade anônima (Authentication), descritos na seção do
acompanhamento.

Como consequência, também **não conseguimos** recuperar seus dados se você perder o celular
sem ter salvo uma cópia — e é por isso que a cópia de segurança existe.

## Crianças e adolescentes

O Lembrô não é direcionado a menores de 13 anos e não coleta dados de ninguém, de qualquer
idade. Se um responsável usar o aplicativo para organizar a rotina de uma criança, os dados
seguem no aparelho do responsável, sob o controle dele.

## Seus direitos (LGPD, artigo 18)

Como todos os dados estão no seu aparelho e sob o seu controle, você exerce seus direitos
diretamente, sem depender de nós e sem prazo de espera:

| Direito | Como exercer |
|---|---|
| **Acessar** os dados | Estão visíveis no aplicativo; "Salvar uma cópia" exporta tudo em arquivo legível |
| **Corrigir** | Editar o lembrete, ou corrigir/apagar um registro no histórico |
| **Portabilidade** | O arquivo da cópia de segurança é JSON aberto, não um formato fechado |
| **Eliminar** | Apagar o lembrete, ou desinstalar o aplicativo — desinstalar remove o banco de dados inteiro |
| **Eliminar o espelho do acompanhamento** | Configurações → Quem me acompanha → **Remover**: corta o acesso e apaga da nuvem tudo o que já foi enviado, no mesmo toque |
| **Revogar consentimento** | Do acompanhamento: o botão Remover. Do resto: desinstalar — não há mais nada nosso para revogar |

Se ainda assim você quiser falar conosco sobre privacidade, use o contato no topo.

## Retenção e eliminação

Os dados ficam no seu aparelho pelo tempo que você quiser. **Desinstalar o aplicativo apaga
o banco de dados.** Não há cópia nossa, portanto não há nada que sobreviva à desinstalação —
exceto os arquivos de cópia de segurança que você mesmo tenha guardado em outro lugar e, se
você usa o acompanhamento, os dias já enviados ao espelho. **Se você usa o acompanhamento e
vai desinstalar, use antes o Remover**: é ele que apaga o espelho na nuvem. Desinstalar sem
isso deixa lá o que já subiu, e a eliminação passa a depender de um pedido pelo contato no
topo.

## Segurança

Os dados residem na área privada do aplicativo, protegida pelo sistema operacional: outros
aplicativos não conseguem lê-la. Fora o espelho do acompanhamento — que só existe com a sua
autorização, viaja cifrado (TLS) e carrega o mínimo descrito acima —, não há transmissão
pela rede, o que elimina a classe inteira de riscos de interceptação e de vazamento em
servidor para todo o resto.

Recomendamos manter a tela de bloqueio do celular ativa, com senha ou biometria — é ela que
protege qualquer aplicativo, inclusive este, se o aparelho for perdido.

## Incidentes

A única base de dados fora do aparelho é o espelho do acompanhamento, descrito acima — com o
mínimo de dado possível, identidade anônima e leitura restrita por regra de servidor. Caso
alguma vulnerabilidade seja identificada no aplicativo ou nessas regras, corrigiremos e
publicaremos uma atualização; se houver risco relevante aos titulares, comunicaremos pelos
canais da loja e por esta página, conforme o artigo 48 da LGPD.

## Mudanças nesta política

A versão anterior desta política prometia: se alguma função passasse a enviar dados para
fora do aparelho, esta página seria atualizada **antes** do lançamento e o aplicativo
pediria **consentimento específico e destacado** na tela. O acompanhamento por um
responsável é exatamente esse caso, e foi assim que ele chegou: descrito aqui antes de
existir na loja, desligado por padrão, e ligado somente pelo seu toque em "Autorizar".

A promessa continua valendo para o que vier: mudança que amplie o que sai do aparelho será
publicada aqui antes, com a data alterada no topo, e nunca ligada em silêncio ou por padrão.

## Lei aplicável

Esta política é regida pela legislação brasileira, em especial a Lei nº 13.709/2018 (LGPD) e
a Lei nº 8.078/1990 (Código de Defesa do Consumidor).
