# Discourse

Olá! Que bom que chegou aqui. Antes de rodar o código é importante você realizar algumas coisas antes.

Vamos precisar seguir esses passos abaixo antes de executar.

1-Instalar Python (3.x+) + pip acessando o link: https://www.python.org/downloads/windows/
(marcar opção de adição do Python do Path)

*No terminal console (CMD), executar os passos 2 ao 4:

2. Confirmar versão do Ptyhon e Pip instalados:
	python --version
	pip --version

3. Instalar Robot Framework
	pip install robotframework
		
3. Instalar biblioteca do Selenium
	pip install robotframework-seleniumlibrary

4. Verificar as dependências instaladas
	pip freeze ou pip list
	
5. Fazer download dos webdrivers e setar os arquivos descompactados na pasta de scripts do python (path) ou na pasta "Windows" no disco "C".
	5.1. Chromedriver (Google Chrome): https://chromedriver.chromium.org/downloads (verificar versão do Chrome e fazer download da compatível)
	5.2. Geckodriver (Firefox): https://github.com/mozilla/geckodriver/releases
	
	
** Observação para as páginas web: Importante abrir manualmente a página do teste (Discourse) para aceitar os cookies, caso nunca tenha aberto.	
