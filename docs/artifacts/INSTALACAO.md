# Circuito Ferradura — Instalação (Windows e macOS)

Versão: v2.0.24

Arquivos desta entrega:

- CircuitoFerradura.exe
- circuito-ferradura-windows-2.0.24.zip
- circuito-ferradura-macos-2.0.24.zip
- circuito-ferradura-site-2.0.24.zip
- apresentacao_circuito_ferradura.html
- checksum.sha256
- checksum.md5

O executável não tem assinatura digital. O demo de console existe só no Windows. No macOS, o pacote abre o curso no navegador.

## Validação de integridade

No PowerShell, na pasta dos artefatos:

```powershell
Get-FileHash -Path .\CircuitoFerradura.exe -Algorithm SHA256
Get-FileHash -Path .\circuito-ferradura-windows-2.0.24.zip -Algorithm SHA256
Get-FileHash -Path .\circuito-ferradura-macos-2.0.24.zip -Algorithm SHA256
Get-FileHash -Path .\circuito-ferradura-site-2.0.24.zip -Algorithm SHA256
```

No macOS ou no Linux:

```bash
shasum -a 256 CircuitoFerradura.exe
shasum -a 256 circuito-ferradura-windows-2.0.24.zip
shasum -a 256 circuito-ferradura-macos-2.0.24.zip
shasum -a 256 circuito-ferradura-site-2.0.24.zip
```

Compare os valores com `checksum.sha256` e `checksum.md5`.

## Windows

1. Descompacte `circuito-ferradura-windows-2.0.24.zip`.
2. Execute `CircuitoFerradura.exe` com duplo clique.
3. Se o Windows SmartScreen avisar que o editor é desconhecido, confirme só se o arquivo veio do canal oficial e os hashes conferem.
4. O curso offline fica em `curso/index.html`, ao lado do executável.
5. A apresentação offline fica em `curso/apresentacao_circuito_ferradura.html`.

## macOS

1. Descompacte `circuito-ferradura-macos-2.0.24.zip`.
2. Abra `abrir-circuito-ferradura.command`.
3. Se o macOS bloquear a primeira execução, clique com o botão direito no arquivo, escolha Abrir e confirme.
4. Alternativa: abra `curso/index.html` no navegador.
5. A apresentação offline fica em `curso/apresentacao_circuito_ferradura.html`.

## HTML offline

1. Descompacte `circuito-ferradura-site-2.0.24.zip`.
2. Abra `curso/index.html`.
3. A apresentação desse pacote é `curso/apresentacao_circuito_ferradura.html`.

## Canal oficial

- Download: https://circuito.caracore.com.br/download.html
- Licença: https://circuito.caracore.com.br/licenca-uso.html
- Feedback: https://circuito.caracore.com.br/canal-feedback.html
- Apresentação no site: https://circuito.caracore.com.br/curso/apresentacao_circuito_ferradura.html

Cara Core Informática — https://circuito.caracore.com.br/
