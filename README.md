Copyleft (ɔ) 2012 Marcos da B. M. Oliveira                                  
                                                                    
This program is free software: you can redistribute it and/or modify        
it under the terms of the GNU General Public License as published by        
the Free Software Foundation, either version 3 of the License, or           
(at your option) any later version.                                         
                                                                    
This program is distributed in the hope that it will be useful,             
but WITHOUT ANY WARRANTY; without even the implied warranty of              
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the               
GNU General Public License for more details.                                
                                                                    
You should have received a copy of the GNU General Public License           
along with this program.  If not, see <http://www.gnu.org/licenses/>.       

jogodaforca.sh 	: Jogo da Forca - GNU EDITION

Site				: http://www.terminalroot.com.br/
Autor				: Marcos da B. M. Oliveira <binbash@linuxmail.org>

Este é o famoso Jogo da Forca , mas escrito em Shell Script , feito pra Linux e
roda no Terminal.

Exemplo:
$ ./jogodaforca.sh
Pressionando CTRL+E ele reseta o jogo.
Pressionando CTRL+A ele sai do jogo

v1.0 2015-08-12 , Marcos Oliveira:
- Versão inicial , jogo funcionando

FIXME 	- O jogo gera BUG quando o número de letras de uma palavra é maior que 10
e não aceita palavras que possuem acento.
TODO  	- Criar uma solução sem alterar essa lógica
XXX   	- Ainda estou analisando uma forma de resolver esse BUG
