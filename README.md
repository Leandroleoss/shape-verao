# 🏋️‍♂️ ShapeVerão Pro 🍎

> **Rastreador de Treino & Dieta Inteligente** — Uma aplicação web moderna, rápida e 100% gratuita projetada para simplificar o acompanhamento da sua evolução física, sem planilhas complexas ou cadastros demorados.

---

## 🚀 O que é o ShapeVerão Pro?

Muitas vezes, o maior obstáculo para quem quer começar a cuidar da saúde é a complexidade dos aplicativos atuais. Ter que calcular gramas exatas de macronutrientes logo no primeiro dia faz muita gente desistir.

O **ShapeVerão Pro** resolve isso trazendo **simplicidade e inteligência**. Com uma interface minimalista e escura (*Dark Mode*), ele calcula automaticamente suas metas de dieta com base no seu peso e objetivo, além de gerenciar seus treinos e evolução em um único lugar.

---

## ✨ Principais Funcionalidades

### 🔮 1. Dieta Inteligente & Calculadora Automática
* **Modo Fácil (Auto):** Digite seu peso, escolha seu objetivo (*Emagrecer/Definição*, *Ganhar Massa/Hipertrofia* ou *Manter Peso/Vida Saudável*) e o app calcula suas metas de Proteínas, Carboidratos e Gorduras instantaneamente com base em fórmulas científicas.
* **Modo Avançado (Manual):** Tem uma dieta do seu nutricionista? Insira suas metas manualmente.
* **Estrutura de Refeições:** Adicione alimentos facilmente e acompanhe as barras de progresso diárias.
* **Banco de Alimentos Geral:** Cadastre novos alimentos para usar quando quiser.

### 🏋️‍♂️ 2. Registro de Treino & Cárdio
* **Fichas Completas:** Gerencie seus treinos (A, B, C), edite exercícios, séries e cargas.
* **Checklist Ativo:** Marque os exercícios concluídos para dar aquela sensação de dever cumprido.
* **Timer de Descanso Integrado:** Cronômetro de 1 minuto acionado com um clique para você não se distrair entre as séries (com aviso sonoro ao finalizar).
* **Diário de Atividades:** Histórico unificado de musculação e sessões de cárdio com cálculo estimado de queima calórica.

### 📈 3. Evolução Visual
* **Histórico de Pesagens:** Registre seu peso com a data atual ou retroativa.
* **Gráfico Dinâmico:** Gráfico de linha interativo (via Chart.js) para você visualizar sua evolução de peso ao longo do tempo.
* **Gerenciador de Histórico:** Altere ou exclua registros antigos facilmente.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído focando em performance, portabilidade e sem dependências pesadas de backend:

* **HTML5** & **CSS3** (Estrutura e semântica)
* **Tailwind CSS** (Estilização moderna, responsiva e utilitária via CDN)
* **JavaScript (ES6+)** (Lógica de negócios, manipulação de estado e cálculos)
* **Chart.js** (Renderização do gráfico de evolução de peso)
* **Font Awesome 6** (Ícones modernos e visuais)
* **LocalStorage API** (Armazenamento persistente direto no navegador do usuário, garantindo **100% de privacidade** dos dados)

---

## 🔒 Privacidade e Custo

* **100% Gratuito:** Sem pegadinhas, sem anúncios e sem necessidade de assinatura.
* **Seus dados são seus:** O aplicativo não envia suas informações para nenhum servidor externo. Tudo fica salvo de forma segura no `localStorage` do seu próprio dispositivo.

---

## 💻 Como Rodar o Projeto

Por ser uma aplicação *Single Page Application (SPA)* pura, você não precisa instalar o Node.js, Docker ou bancos de dados.

1. Faça o clone deste repositório:
   ```bash
   git clone [https://github.com/Leandroleoss/shape-verao.git](https://github.com/Leandroleoss/shape-verao.git)
