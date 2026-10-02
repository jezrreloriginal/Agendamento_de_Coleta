# 📦 · Gestão de Coletas e Carretos

Sistema web integrado e responsivo desenvolvido para otimizar e automatizar a rotina operacional de gestão de coletas, entregas e carretos, sincronizando dados diretamente com o Google Planilhas via Apps Script.

---

## 💡 Sobre o Projeto
Este é um **projeto pessoal de desenvolvimento de software** criado sob medida para automatizar e otimizar tarefas logísticas e administrativas do dia a dia. A aplicação foi concebida para uso particular e continuará hospedada e disponível enquanto for de interesse do autor, mantendo-se integralmente protegida pelas diretrizes de **propriedade intelectual** e direitos de criação de software.

---

## 🚀 Funcionalidades Principais

1. **🚚 Fretes do Dia (Dashboard Principal)**
   * Listagem rápida e organizada em tabela dos fretes agendados para a data corrente.
   * Acompanhamento de status em tempo real com etiquetas coloridas e alteração instantânea.
   * Atalho de links diretos para abertura de rotas no Google Maps/Waze.
   * Botão de **cópia rápida** para o WhatsApp e geração de versão limpa para **impressão/PDF**.

2. **📅 Calendário de Fretes**
   * Visão geral mensal estruturada em formato de calendário em modal.
   * Identificação visual por dia dos fretes pendentes e concluídos através de etiquetas com códigos de cores.

3. **🔍 Filtros e Períodos Personalizados**
   * Alternância rápida entre visualização de **Hoje**, **Esta Semana** ou **Período Personalizado** (com seleção livre de data inicial e final).
   * Filtros cruzados por status e motorista responsável.

4. **📄 Leitor Automático de DANFE (PDF)**
   * Importação de arquivos PDF de Notas Fiscais para extração automática de dados como número da NF, destinatário, endereço, bairro, CEP e telefone.

5. **☁️ Sincronização em Nuvem (Google Sheets)**
   * Banco de dados integrado via Google Apps Script, garantindo persistência em nuvem, além de opções de backup e importação via planilhas Excel (`.xlsx`).

---

## 📖 Tutorial de Primeiro Acesso

Siga o passo a passo abaixo para configurar e realizar o primeiro acesso ao sistema:

### Passo 1: Abrindo a Aplicação
* Baixe ou clone o arquivo `index.html` do repositório.
* Dê um duplo clique no arquivo para abri-lo diretamente em qualquer navegador moderno (Google Chrome, Microsoft Edge, etc.).

### Passo 2: Configurando o Banco de Dados (Google Planilhas)
Para sincronizar as informações com a sua planilha na nuvem:
1. Clique na aba superior **"☁️️ Configurações / Planilha"**.
2. No campo **Link do Apps Script**, cole a URL de implantação da sua API web (que termina em `/exec`).
3. Insira a **Senha** de segurança configurada no seu script.
4. Clique no botão **"🔗 Conectar"** e em seguida em **"🔄 Sincronizar"**. O sistema validará a conexão e puxará os dados automaticamente.

### Passo 3: Cadastrando Motoristas
1. Vá até a aba **"🚛 Motoristas"**.
2. Insira o nome do motorista e o telefone (opcional).
3. Clique em **Cadastrar motorista** para salvá-lo na lista de seleção dos fretes.

---

## ⚙️ Guia de Uso das Funções

* **Cadastrar Coleta:** Acesse a aba *Novo Agendamento*, arraste ou selecione o PDF da Nota Fiscal para preencher os campos automaticamente (ou digite manualmente), escolha o motorista, defina o valor e clique em **Salvar agendamento**.
* **Copiar Fretes do Dia:** Na aba *Fretes de Hoje*, clique em **"📋 Copiar fretes do dia"** para gerar um texto formatado pronto para ser colado no chat do WhatsApp.
* **Imprimir Relatório Limpo:** Clique no botão **"🖨️ Imprimir / PDF"** na tela inicial para gerar um documento formatado exclusivamente com as entregas do dia, ocultando menus e botões desnecessários.

---

## ⚖️ Propriedade Intelectual e Uso
Este software, sua arquitetura, código-fonte e lógica associada representam uma solução de desenvolvimento pessoal voltada à eficiência de processos individuais. Todos os direitos de propriedade intelectual são reservados ao criador. O acesso, visualização ou clonagem do repositório são permitidos para fins de portfólio e estudo, sendo vedada a comercialização ou redistribuição sem autorização prévia.
