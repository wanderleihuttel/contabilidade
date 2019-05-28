#### Procedimentos para funcionar o e-CAC (https://www2.dataprev.gov.br/Ecac/LoginServlet)

*Este procedimento foi testado em diversas máquinas utilizando Windows 10 atualizadas, 
e na maioria das máquinas que foram testadas o procedimento funcionou corretamente.*


#### Windows 10

1) Baixar arquivo de hierarquias do certisign e executar

    http://drivers.certisign.com.br/hierarquias/icp_brasil/hierarquia-completa/InstaladorCadeiaV5.exe


2) Baixar cadeias do iti.gov e abrir os arquivos inf:
   - http://acraiz.icpbrasil.gov.br/ICP-Brasilv5.crt
   - http://acraiz.icpbrasil.gov.br/ICP-Brasilv8.crt
   - http://acraiz.icpbrasil.gov.br/ICP-Brasilv9.crt
   - http://acraiz.icpbrasil.gov.br/repositorio/v1_v2_v5_v8_v9_msie.p7b
   - http://acraiz.icpbrasil.gov.br/repositorio/v1_v2_v5_v8_v9_goochr.p7b

     Quando for instalar utilizar as seguintes opções:
     - Selecionar a opção **"Colocar todos os certificados no repositório a seguir"** e clicar em procurar
     - Selecionar **"Autoridade de Certificação Raiz Confiáveis"** e em avançar

3) Executar o utilitário do Windows: **"certlm.msc"**" (certificados computador local)
   - Selecionar no lado esquerdo **"Autoridade de Certificação Raiz Confiáveis / Certificados"**
   - Clicar no certificado **"Autoridade Certificadora Raiz Brasileira v5"**
   - Clicar com o botão direito do mouse no certificado acima e clicar na opção "**Propriedades**"
   - Alterar para **"Ativar todas as finalidades deste certificado"**
   
4) Acessar o e-CAC
   - E acesse a opção de **"Certidões e Situação Fiscal"** => **"Consulta Pendências - Situação Fiscal-Relatório Complementar"**
   
5) Caso não funcione ainda, acesse em uma outra aba o endereço (https://www2.dataprev.gov.br/Ecac/LoginServlet).
E agora ele vai permitir continuar, clicar na opçao de continuar quando o site não for seguro.

6) Acessar a opção do e-CAC normalmente.
