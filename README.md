# JNX-Firmwares

Repositório de firmwares do aplicativo **JNX MOD** ([JNX-Updater](https://github.com/MeoWDev-MOD/JNX-Updater)).

## Como é organizado

Cada firmware é um [release](../../releases):

| Campo | Padrão | Exemplo |
|---|---|---|
| Tag | a versão do firmware | `1.2.0` |
| Título | `Firmware <versão> ( AMS <versão> )` | `Firmware 1.2.0 ( AMS 1.0.0 )` |
| Texto | versão, compatibilidade e SHA-256 do zip | |
| Arquivo (asset) | `<versão>.zip` | `1.2.0.zip` |

O aplicativo lista esses releases na aba **Firmwares** e extrai o conteúdo do zip em `/firmware` no cartão SD.

## Regra do repositório

Publique aqui **somente** firmware que você criou ou que você tem permissão de distribuir.
Não publique arquivos de terceiros sem autorização, nem chaves. Se o titular dos direitos pedir a remoção de um arquivo,
ele será removido.
