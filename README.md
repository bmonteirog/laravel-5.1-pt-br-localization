# Arquivos de linguagem do Laravel 5.1 - Português do Brasil

## Instalação

1. Clonar este projeto para uma pasta dentro de `resources/lang/`
  ```
  $ cd resources/lang/
  $ git clone git@github.com:bmonteirog/laravel-5.1-pt-br-localization.git
  ```

2. Configurar o Framework para utilizar a linguagem como Default
  ```
  // Linha 55 do arquivo config/app.php
  'locale' => 'pt-br',
  ```

3. (opcional) É recomendado remover o submódulo do git, para que você possa incluir e versionar os arquivos deste projeto no seu repositório, evitando criar um gitlink
  ```
  $ mv pt-br pt-br_tmp
  $ git submodule deinit laravel-5.1-pt-br-localization
  $ git rm laravel-5.1-pt-br-localization
  $ mv pt-br_tmp pt-br
  $ git add pt-br
  ```