#Pré-Requisitos

&nbsp;
### 1 - Instalação versão mais recente
&nbsp;

No site [SAP Development Tools](https://tools.hana.ondemand.com/#abap) a SAP disponibiliza o procedimento para instalação da versão mais recente estável do Eclipse com ADT (**ABAP Development Tools**). As versões mais recentes do Eclipse utilizam JRE 11, portanta caso tenha problemas com essa versão ou alguma incompatibilidade, use a versão Oxygen do Eclipse com o JAVA JDK 8.

Se utilizar a versão disponibilizada no SAP Development Tools, ignore os passos 2 e 3.

&nbsp;
### 2 - Instalação do JAVA 8 JDK
&nbsp;

&nbsp;
### Windows
&nbsp;

Acesse o site da Oracle e instale o [Java JDK 8](https://www.oracle.com/br/java/technologies/javase/javase-jdk8-downloads.html) (instalar o update mais recente, desde que seja Java 8. Atentar ao fato que é preciso instalar o JDK e não o JRE, e o Java precisa estar na versão 8 (versões anteriores não servem).

Após a instalação, verifique se existe a variável de sistema JAVA_HOME e se ela está apontando para o diretório de instalação do seu Java JDK.

&nbsp;
![JAVA_00](img/JAVA/JAVA_00.jpg){: .center}

![JAVA_01](img/JAVA/JAVA_01.png){: .center}

![JAVA_02](img/JAVA/JAVA_02.png){: .center}

![JAVA_03](img/JAVA/JAVA_03.png){: .center}
&nbsp;

&nbsp;
## 3 - Instalação do Eclipse
&nbsp;

Para instalação do Eclipse é preciso ter o JAVA instalado previamente.

&nbsp;
### Windows
&nbsp;

Acesse o site do [Eclipse](http://www.eclipse.org/oxygen/) e faça download do [Eclipse Oxygen 4.7](https://www.eclipse.org/downloads/download.php?file=/oomph/epp/oxygen/R2/eclipse-inst-win64.exe)

Instale a opção "Eclipse IDE for Java Developers"

&nbsp;
![Eclipse_01](img/Eclipse/EclipseInstall_01.png){: .center}
&nbsp;

&nbsp;
## 4 - Instalação do ADT (ABAP Development Tools)
&nbsp;

&nbsp;
### Windows
&nbsp;

Os passos a seguir estão descritos no site [SAP Development Tools ABAP](https://tools.hana.ondemand.com/#abap) para instalar o plugin ADT (ABAP Development Tools) no Eclipse Oxygen.

* Abra o Eclipse Oxygen; 

* Vá em _**Help>Install New Software..**_;

&nbsp;
![ADT_01](img/ADT/ADT_01.jpg){: .center}
&nbsp;

* Se tiver usado a versão do SAP Development Tools, adicione o repositório informado no site da SAP. Caso tenha usado a versão do Eclipse Oxygen, adicione o repositório **https://tools.hana.ondemand.com/oxygen** e pressione **Enter**;

&nbsp;
![ADT_02](img/ADT/ADT_02.jpg){: .center}

![ADT_03](img/ADT/ADT_03.jpg){: .center}

![ADT_04](img/ADT/ADT_04.jpg){: .center}
&nbsp;

* Marque as opções **ABAP Development Tools** e **SAP HANA Tools** e clique em **Next**;

&nbsp;
![ADT_05](img/ADT/ADT_05.jpg){: .center}
&nbsp;

* Clique novamente em **Next**, aceite os termos de licença e clique em **Finish**;

&nbsp;
![ADT_06](img/ADT/ADT_06.jpg){: .center}

![ADT_07](img/ADT/ADT_07.jpg){: .center}
&nbsp;

* O Eclipse vai começar a baixar e instalar os Plugins de ABAP e de HANA; 

&nbsp;
![ADT_08](img/ADT/ADT_08.jpg){: .center}
&nbsp;

* Caso apareça algum warning, basta clicar em Install **Anyway**;

&nbsp;
![ADT_09](img/ADT/ADT_09.jpg){: .center}
&nbsp;

* Após conclusão da instalação, será necessário reiniciar o Eclipse Oxygen;

&nbsp;
![ADT_10](img/ADT/ADT_10.jpg){: .center}
&nbsp;

Para verificar se a instalação dos plugins ocorreu com sucesso, basta seguir os seguintes procedimentos:  

* Acesse o menu **Window>Perspective>Open Perspective>Other...**;

&nbsp;
![ADT_11](img/ADT/ADT_11.jpg){: .center}
&nbsp;

* Deverá ter as duas perspectivas na lista de perspectivas, a de ABAP e a de HANA; 

&nbsp;
![ADT_12](img/ADT/ADT_12.jpg){: .center}

![ADT_13](img/ADT/ADT_13.jpg){: .center}
&nbsp;