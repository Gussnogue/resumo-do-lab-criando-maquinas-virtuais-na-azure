# resumo-do-lab-criando-maquinas-virtuais-na-azure
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

**Criar uma VM Windows no Azure pelo Portal**

## Passos

1. **Entrar no Portal Azure**  
   Acesse [portal.azure.com](https://portal.azure.com).

2. **Criar recurso**  
   Vá em **Criar um recurso** → **Máquina Virtual**.

3. **Configurações básicas**  
   - Selecione **Assinatura** e **Grupo de Recursos**.  
   - Defina:
     - **Nome da VM**
     - **Região**
     - **Imagem** (ex.: *Windows Server 2019 Datacenter*)  
     - **Tamanho da VM**  
   - Configure credenciais de **Usuário Administrador** e **Senha**.

4. **Rede**  
   - Crie ou escolha uma **Rede Virtual** e **Sub-rede**.  
   - Habilite **IP público** (se necessário).  
   - Configure **Portas de entrada** (ex.: **RDP - 3389**).

5. **Discos**  
   - Escolha o tipo de disco do SO (**SSD** ou **HDD**).

6. **Revisar e criar**  
   - Revise todas as configurações.  
   - Clique em **Criar**.

7. **Implantação**  
   - Aguarde a conclusão da criação da VM.

8. **Conectar na VM**  
   - No recurso da VM, clique em **Conectar** → **RDP**.  
   - Baixe o arquivo `.rdp`.  
   - Entre usando **usuário e senha** configurados.

[https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
