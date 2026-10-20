<div align="center">

# SyncDay

**Organize o dia. Mantenha o foco. Retome o que importa.**

Sua agenda de eventos e tarefas em um só lugar, com Linha do Tempo, Kanban e revisão de pendências.

![Android 7.0 ou superior](https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-Jetpack%20Compose-7F52FF?logo=kotlin&logoColor=white)
![Distribuição](https://img.shields.io/badge/Download-GitHub%20Releases-181717?logo=github&logoColor=white)

**[⬇ Baixar SyncDay para Android](https://github.com/gustavoPassone/syncday-showcase/releases/latest/download/SyncDay.apk)**

[Ver versões e novidades](https://github.com/gustavoPassone/syncday-showcase/releases) · [Relatar um problema](https://github.com/gustavoPassone/syncday-showcase/issues)

</div>

---

## Uma agenda que acompanha seu ritmo

Alguns compromissos têm hora marcada. Outras tarefas precisam apenas encontrar espaço no seu dia. O SyncDay reúne os dois jeitos de se organizar, com uma visão diária simples e acesso ao seu histórico.

| Recurso | Como ajuda você |
| --- | --- |
| **Linha do Tempo** | Visualize os eventos e compromissos com horário. |
| **Kanban** | Acompanhe tarefas flexíveis por status, do planejamento à conclusão. |
| **Prioridades** | Identifique o que merece mais atenção. |
| **Revisão de pendências** | Traga tarefas anteriores para hoje ou ignore o lembrete, uma a uma ou em lote. |
| **Dias com Tarefas** | Consulte seu histórico por data, com a quantidade de tarefas e navegação por páginas. |
| **Busca** | Encontre tarefas e volte ao dia em que foram registradas. |
| **Lembretes** | Receba avisos de eventos e acompanhamentos ao longo do dia. |
| **Sincronização** | Acesse perfil e tarefas vinculados à sua conta com Firebase. |

Ignorar uma pendência preserva a tarefa no histórico. Você também pode consultar dias anteriores e alterar o status das tarefas; a criação de novas tarefas fica disponível para hoje e datas futuras.

## Instalar no Android

**Requisito:** Android 7.0 ou superior. É necessária conexão com a internet para entrar na conta e sincronizar dados.

1. No celular, toque em **[Baixar SyncDay](https://github.com/gustavoPassone/syncday-showcase/releases/latest/download/SyncDay.apk)**.
2. Abra o arquivo `SyncDay.apk` baixado.
3. Se o Android solicitar, permita a instalação pela origem usada para abrir o arquivo, como o navegador ou o gerenciador de arquivos.
4. Confirme a instalação e abra o SyncDay.
5. Entre com Google ou com e-mail e senha. Autorize as notificações se quiser receber lembretes.

O arquivo `.apk` é o instalador do aplicativo. Os arquivos **Source code (zip)** e **Source code (tar.gz)** exibidos pelo GitHub não são instaladores.

Se o download direto ainda não estiver disponível, abra a [página de releases](https://github.com/gustavoPassone/syncday-showcase/releases) e procure o arquivo `SyncDay.apk` nos assets da versão publicada.

## Receber atualizações

Ao entrar na tela inicial com internet, o SyncDay consulta a versão estável mais recente neste repositório. Quando há uma atualização, o app apresenta a opção de baixar o novo APK e abrir a confirmação de instalação do Android.

Você também pode baixar a nova versão manualmente na [página de releases](https://github.com/gustavoPassone/syncday-showcase/releases). Para atualizar uma instalação oficial, instale o novo APK por cima do anterior, sem desinstalar o app.

As atualizações oficiais mantêm o mesmo identificador e a mesma assinatura. O Android sempre solicita a confirmação de instalação; se necessário, autorize o SyncDay a instalar aplicativos e retorne ao app para continuar.

## Dados e conexão

O SyncDay utiliza Firebase Authentication para autenticação e Cloud Firestore para sincronizar perfil e tarefas. O aparelho mantém um cache local do histórico já carregado. Login e confirmação das alterações sincronizadas dependem da conexão com a internet.

Os horários dos lembretes usam o horário local do aparelho. A entrega também depende das permissões e configurações de bateria e alarmes do Android.

## Ajuda e sugestões

Encontrou uma falha ou tem uma ideia para melhorar o SyncDay? [Abra uma issue](https://github.com/gustavoPassone/syncday-showcase/issues) com:

- Modelo do aparelho e versão do Android.
- Versão do SyncDay instalada.
- Passos para reproduzir o problema e o resultado esperado.

Evite incluir senhas, tokens ou informações pessoais nas issues públicas. As mudanças de cada versão ficam nas [notas de lançamento](https://github.com/gustavoPassone/syncday-showcase/releases).

---

**Sobre este repositório:** este é o showcase e canal de distribuição do SyncDay. O código-fonte do aplicativo é mantido em um repositório privado.

Desenvolvido por [Gustavo Passone](https://github.com/gustavoPassone).
