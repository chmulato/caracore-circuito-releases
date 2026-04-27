# Circuito Ferradura - Instalacao (Windows e macOS)

Arquivos desta entrega:
- CircuitoFerradura.exe
- circuito-ferradura-site-2.0.0.zip
- circuito-ferradura-windows-2.0.0.zip
- circuito-ferradura-macos-2.0.0.zip
- apresentacao_circuito_ferradura.html
- checksum.sha256
- checksum.md5
- INSTALACAO.md (este arquivo)

## Validacao de integridade

No PowerShell, na pasta de artefatos:

```powershell
Get-FileHash -Path .\CircuitoFerradura.exe -Algorithm SHA256
Get-FileHash -Path .\CircuitoFerradura.exe -Algorithm MD5
```

Compare os valores com os arquivos `checksum.sha256` e `checksum.md5`.

## Requisitos Windows

- Windows 10 ou superior (64 bits)
- 200 MB de espaco livre
- Conexao com internet: nao necessaria

## Execucao do aplicativo Windows

1. Execute `CircuitoFerradura.exe` em duplo clique.
2. Se o Windows SmartScreen exibir um aviso, confirme apenas se o arquivo foi baixado do canal oficial e os hashes conferem.
3. O aplicativo abre localmente em uma janela de terminal e pode abrir o curso completo no navegador.

Para uma entrega completa, use `circuito-ferradura-windows-2.0.0.zip`: ele contem o executavel, `curso/` e `assets/` no mesmo pacote.

## Execucao no macOS

1. Baixe `circuito-ferradura-macos-2.0.0.zip`.
2. Descompacte o arquivo.
3. Abra `abrir-circuito-ferradura.command`.
4. Se o macOS bloquear a primeira execucao, clique com o botao direito no arquivo, escolha Abrir e confirme.

Alternativa: abra `curso/index.html` diretamente no Safari, Chrome ou Firefox.

## Uso no navegador (HTML completo)

1. Descompacte `circuito-ferradura-site-2.0.0.zip`.
2. Abra `curso/index.html` no navegador para acessar a apresentacao atualizada.
3. Para a apresentacao individual, abra `apresentacao_circuito_ferradura.html`.

## Desinstalacao

Remova os arquivos baixados/descompactados. Nao ha instalador MSI nem servico residente nesta entrega.

## Canal oficial

- Pagina de download: ../download.html
- Licenca: ../licenca-uso.html
- Suporte (loja Circuito Ferradura): https://circuito.caracore.com.br/canal-feedback.html

---

> Versao: v2.0.0
> Cara Core Informatica — loja: https://circuito.caracore.com.br/
