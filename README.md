# ERP_MT PDV: instaladores

Programa do computador do caixa do ERP_MT. Abre o sistema da loja numa janela própria e imprime a
nota e os comprovantes **direto na impressora de cupom**, sem abrir PDF.

Este repositório só guarda os instaladores (em **Releases**). Os links abaixo sempre baixam a versão mais nova:

| Sistema | Baixar |
|---|---|
| Windows 10/11 (64 bits) | [ERP_MT-PDV-Setup.exe](https://github.com/ERP-MT/erp-mt-pdv-instaladores/releases/latest/download/ERP_MT-PDV-Setup.exe) |
| Ubuntu / Debian / Mint (64 bits) | [erp-mt-pdv.deb](https://github.com/ERP-MT/erp-mt-pdv-instaladores/releases/latest/download/erp-mt-pdv.deb) |

## Como instalar

1. Instale antes o **driver da impressora de cupom** (Elgin i8/i9 etc.) e faça uma impressão de teste pelo sistema.
2. Instale o programa:
   - **Windows:** dois cliques no `.exe`. Se aparecer o aviso do SmartScreen, clique em
     **Mais informações → Executar assim mesmo** (o instalador não tem assinatura paga).
     No Chrome, se avisar que o arquivo não é baixado com frequência, clique em **Manter**.
   - **Linux:** dois cliques no `.deb` (Central de Programas) ou `sudo apt install ./erp-mt-pdv.deb`.
3. Na primeira vez, o programa abre o **assistente**: digite o endereço do sistema da loja,
   escolha a impressora e o papel, faça o **Imprimir teste** e clique em **Concluir**.

Para mudar depois: tecla **Alt → PDV → Configurar novamente**.
