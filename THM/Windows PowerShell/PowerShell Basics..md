
- Comandos no PowerShell são conhecidos como cmdlets e seguem uma convenção de Verb-Noun. 
- O "Verb" descreve a ação e o "Noun" especifica o objeto no qual ação irá agir

#### Basic Cmdlets

| Basic Cmdlets       | Descrição                                                                |
| ------------------- | ------------------------------------------------------------------------ |
| Get-Command         | Lista os comandos que podem ser utilizados                               |
| Get-Help            | Detalha informações sobre cmdlets (Incluindo uso, parametros e exemplos) |
| Get-Alias           | Lista todos os shortcuts dos comandos                                    |
| Get-ChildItem -Path | Lista arquivos e diretórios na localização -path (parâmetro)             |
| Set-Location        | Muda o diretório para o -path especificado                               |
| New-Item -Path      | Cria novo item. Tem que especificar o path e o type(arquivo/diretório)   |
| Remove-Item -Path   | Exclui diretórios e arquivos                                             |
| Copy-Item -Path     | Copia arquivos e diretórios                                              |
| Move-Item -Path     | Move arquivos e diretórios                                               |
| Get-Content -Path   | Similar a "cat"                                                          |
| Find-Module         | Procura modulos online em repositórios                                   |

- Há filtros que podem ser utilizados para diminuir essas listas usando propriedades especificas.

``` shell
Get-Command -CommandType "Function"
Get-Help New-LocalUser
Set-Location -Path ".\Documents"
New-Item -Path ".\navi-room\navi-bed" -Itemtype "Directory"
Remove-Item -Path ".\navi-room\navi-bed\navi-diary.txt"
Get-Content -Path ".\navi-panties"

```
