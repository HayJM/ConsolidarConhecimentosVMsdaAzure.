# 📘 Resumo da Aula - Máquinas Virtuais no Azure  

Este repositório contém um resumo do que aprendi durante o laboratório sobre **Máquinas Virtuais no Azure**, no qual explorei conceitos fundamentais de computação em nuvem e pratiquei a criação e configuração de uma VM no **Portal do Azure**.  

📖 Referência: [Criar uma máquina virtual do Windows no Portal do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)  

---

## 🎯 O que eu aprendi nesta aula  

- **Conceito de Máquinas Virtuais (VMs):**  
  Entendi que uma VM é como um "computador dentro do computador", permitindo criar e executar sistemas operacionais e aplicações em um ambiente isolado.  

- **Benefícios do uso de VMs no Azure:**  
  - **Elasticidade:** capacidade de aumentar ou reduzir recursos conforme a demanda.  
  - **Escalabilidade:** permite atender mais usuários sem perder desempenho.  
  - **Alta disponibilidade:** serviços rodando com menos risco de interrupção.  
  - **SLA (Service Level Agreement):** garantia de disponibilidade definida pelo provedor.  

- **Portal do Azure como ferramenta de gerenciamento:**  
  O portal facilita a criação, configuração e monitoramento de VMs sem necessidade de comandos complexos.  

---

## 🛠️ Passo a Passo da Aula  

### 1. Criação da VM no Portal do Azure  
- Acessar o **[portal.azure.com](https://portal.azure.com/)**.  
- Selecionar **Criar recurso > Computação > Máquina Virtual**.  
- Definir:  
  - Assinatura e Grupo de Recursos.  
  - Nome da VM (ex.: `MinhaVMWindows`).  
  - Região (a mais próxima do usuário).  
  - Imagem (Windows Server ou Windows 10/11).  
  - Tamanho (como Standard_B1s, ideal para testes).  

---

### 2. Configuração de Credenciais  
- Criar **usuário administrador** e senha forte.  
- Habilitar portas de acesso, como **RDP (3389)** para conectar via área de trabalho remota.  

---

### 3. Revisão e Implantação  
- Conferir todas as configurações.  
- Clicar em **Revisar + Criar** para iniciar a implantação da VM.  

---

### 4. Acesso à Máquina Virtual  
- Usar a opção **Conectar (RDP)** no portal.  
- Baixar o arquivo RDP gerado.  
- Conectar-se com usuário e senha definidos.  
- A partir daí, utilizar a VM como se fosse um computador físico.  

---

## ✅ Conclusão da Aula  

Este laboratório me ajudou a:  
- Compreender o papel das **máquinas virtuais** em ambientes de nuvem.  
- Criar e configurar uma VM de forma prática e rápida.  
- Entender conceitos importantes como **elasticidade, escalabilidade, SLA e alta disponibilidade**.  
- Documentar o processo de forma clara usando **GitHub e Markdown**.  

Essa prática é essencial para quem deseja trabalhar com **infraestrutura em nuvem**, desenvolvimento de sistemas modernos e soluções que exigem alta confiabilidade.  

---
