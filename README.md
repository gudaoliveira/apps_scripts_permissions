# Permissões do Google Apps Script

Este é um tutorial simples para ensinar como conceder permissões aos seus scripts no Google Apps Script para a execução.

## Por que preciso fazer isso?

Ao executar o Google Apps Script, especialmente quando ele interage com serviços externos ou requer acesso a determinados dados, muitas vezes é necessário conceder permissões. Esta é uma medida de segurança projetada para garantir que você, como proprietário do script, esteja ciente e aprove as ações que o script realizará. Aqui estão as razões comuns pelas quais você pode precisar dar permissões para seu Google Apps Script ser executado:

1. **Acesso a Serviços Externos:**
   - Permissão para interagir com serviços externos como Gmail, Google Drive, etc.

2. **Autorização para Escopos Sensíveis:**
   - Aprovação para ações que exigem escopos de autorização específicos.

3. **Consentimento do Usuário:**
   - Permissão do usuário para acessar seus dados (por exemplo, Google Sheets, Calendário).

4. **Acesso à API:**
   - Configuração para APIs avançadas do Google no Console do Google Cloud.

5. **Revisão de Segurança para Complementos Publicados:**
   - Necessário para complementos publicados atenderem aos padrões de segurança e privacidade.

6. **Permissões para Disparadores:**
   - Permissões adicionais para scripts que são executados automaticamente em intervalos.

Portanto, é sempre necessário ter cautela ao conceder permissões a scripts, especialmente aqueles desenvolvidos por terceiros. Conceda acesso apenas a scripts de fontes confiáveis e revise as permissões solicitadas para entender quais ações o script realizará.

## Como conceder acesso?

<div align="center">
Na primeira vez que você executar qualquer script em qualquer projeto pela primeira vez, ele mostrará a pop-up de permissões, clique em **"OK"** aqui
<br><br>

![primeira pop-up](01.png)

Em seguida, ele pedirá para você fazer login na conta à qual deseja conceder as permissões

![faça login](02.png)

Depois disso, mostrará esta mensagem. Aqui diz que o Google não verificou este app, porque o script não é feito pelo Google, mas por um autor de terceiros. Aqui, clique na opção **"Avançado"**

![O Google não verificou este script](03.png)

Em seguida, basta clicar em "Acessar _seu_projeto_aqui_"

![Acessar o projeto](04.png)

Depois disso, mostrará todas as permissões que você precisa conceder ao projeto para que ele seja executado corretamente, aqui é só clicar em **"Permitir"**

![finalmente, permita que o projeto execute os scripts](05.png)

# É isso, agora você pode executar todos os scripts corretamente, aproveite!

</div>
