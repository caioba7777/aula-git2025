# Comandos Git 
Neste arquivo serão apresentado os comandos git para uso futuro.

## No primeiro uso em um computador 
Para que o git avise e saiba quem fez as alterações é necessário configurar o usuário nas configurações globais do git.
```bash 
git config --global user.name "Caio Daniel Reis"

git config --global user.email "caiodenny22@hotmail.com"
```
### Estando dentro de uma pasta
Para iniciar. Usamos esse comando apenas uma vez 
```bash 
git init 
```
Para saber do status do arquivo. Ele pode ser utilizado a qualquer momento para saber a situação da pasta.
Se ele estiver vermelho, precisa adicionar os arquivos, se estiver verde, estão prontos para salvar (commit)
```bash
git status 
```
Para adicionar algo ao arquivo 
```bash
git add 
```
Para informar que salvamos
```bash
git commit -m "MSG"
``` 