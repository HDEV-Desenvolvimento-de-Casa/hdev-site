# 🅿️ Desafio HDEV — EstacionamentoOn

O **Desafio EstacionamentoOn** faz parte da trilha prática da comunidade **HDEV | Desenvolvimento de Casa**, trazendo um projeto completo para você desenvolver suas habilidades reais criando um sistema **ponta a ponta** de gestão de estacionamento.

Este desafio foi criado para simular um cenário real, com foco em lógica de negócio, persistência local, regras de cálculo e uma interface clara e funcional — podendo ser desenvolvido em **qualquer tecnologia**, tanto **Web** quanto **Desktop**.

---

## 🚀 Visão Geral do Desafio

Você deverá criar um sistema similar ao **EstacionamentoOn**, permitindo controlar veículos estacionados, registrar entradas, calcular permanência e realizar a baixa final com cobrança automática, respeitando as regras definidas.

A entrega deve incluir:
- Código-fonte completo  
- Banco de dados SQLite local  
- README bem documentado  
- Demonstração em vídeo  

Participantes que concluírem recebem o **Badge de Participação**, e os melhores projetos recebem o **Badge de Destaque** da comunidade.

---

## 🔧 Funcionalidades Obrigatórias

Seu projeto deve implementar obrigatoriamente:

- Cadastro de veículos (Placa, Modelo, Cor)  
- Registro automático da data e hora de entrada  
- Cálculo de permanência e valor total  
- Baixa com data/hora de saída  
- Atualização automática do status  
- Bloqueio de edição para veículos finalizados  
- Interface funcional (moderna para Web, intuitiva para Desktop)  
- Login e Home com autenticação simples  

---

## 💰 Regras de Cobrança

A cobrança deve ser calculada automaticamente com base nas regras:

- **Primeiras 2 horas → R$ 18,00**  
- **Hora adicional ou fração → R$ 5,00**  

O sistema deve fazer o cálculo automaticamente no momento da baixa.

---

## 🧱 Estrutura do Banco (SQLite)

A estrutura recomendada é:

```sql
CREATE TABLE Veiculos (
    Id INTEGER PRIMARY KEY AUTOINCREMENT,
    Placa TEXT NOT NULL,
    Modelo TEXT,
    Cor TEXT,
    DataEntrada DATETIME NOT NULL,
    HoraEntrada TEXT NOT NULL,
    DataSaida DATETIME,
    ValorPago DECIMAL(10,2),
    Status TEXT NOT NULL
);
````

---

## 🎓 O que este desafio avalia?

✔ Lógica de programação
✔ Estruturação de projeto
✔ Regras de negócio reais
✔ Capacidade de documentação
✔ Organização de pastas
✔ Fluidez e clareza da interface
✔ Uso correto do SQLite

Utilize a tecnologia que preferir — o importante é entregar uma solução funcional.

---

## 🛠 Tecnologias possíveis

Você pode criar o sistema em:

### **Backend**

* ASP.NET
* Node.js
* Python (Flask/Django)
* PHP (Laravel)
* Java (Spring Boot)

### **Frontend (se Web)**

* React
* Vue
* Angular
* Bootstrap
* Tailwind

### **Desktop**

* C# (WinForms/WPF)
* Python (Tkinter/PyQt)
* JavaFX
* Electron

---

## 🚀 Como Participar

1. Faça o **fork** do repositório oficial:
   👉 [https://github.com/HDEV-Desenvolvimento-de-Casa/hdev-desafios](https://github.com/HDEV-Desenvolvimento-de-Casa/hdev-desafios.git)

2. Desenvolva sua solução no seu repositório.

3. Documente tudo no README da sua entrega.

4. Grave um vídeo curto mostrando o funcionamento completo.

5. Crie uma **issue de entrega** no repositório oficial, incluindo:

   * Link do seu repositório
   * Link do vídeo
   * Observações importantes

Instruções detalhadas estão em:
👉 `COMO-PARTICIPAR.md` do repositório oficial

---

## 🏅 Badges do Desafio

Participação:
![Badge Participação](https://github.com/HDEV-Desenvolvimento-de-Casa/hdev-assets/blob/main/badges/estacionamentoon/estacionamentoon_participacao.png?raw=true)


Destaque:
![Badge Destaque](https://github.com/HDEV-Desenvolvimento-de-Casa/hdev-assets/blob/main/badges/estacionamentoon/estacionamentoon_destaque.png?raw=true)
Mais informações em:
👉 `BADGES.md`

---

## 🧩 Repositório do Desafio

Acesse a versão oficial do desafio no GitHub:
🔗 **[https://github.com/HDEV-Desenvolvimento-de-Casa/hdev-desafios/tree/main/iniciante/desafio-estacionamentoon](https://github.com/HDEV-Desenvolvimento-de-Casa/hdev-desafios/tree/main/iniciante/desafio-estacionamentoon)**

---

## 📣 Sobre a Comunidade

O desafio faz parte da iniciativa **HDEV | Desenvolvimento de Casa**, que reúne estudantes, profissionais e entusiastas para aprender, praticar e evoluir através de projetos reais.

Participe, estude com outros desenvolvedores e conquiste seu lugar no ranking da comunidade!

---

