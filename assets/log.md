[<<< cодержание](../readme.md)

[< Проверка состояния репозитория](./status.md)

---

## История коммитов

Получить список произведенных изменений можно командой:
> ```bash=
> git log
> ```

При этом ожидаемый результат, пример:
```bash=
$ git log
commit 460eeed2a80dfe8023d73f926fd6000b846cb21a (HEAD -> main, origin/main)
Author: Nick-Voskoboinikov <Nick@Voskoboinikov.com>
Date:   Fri Jul 22 23:26:24 2022 +0300

    test2

commit 4f9c252e5cab47fb8eed4228e1883602287b980b
Author: Nick-Voskoboinikov <Nick@Voskoboinikov.com>
Date:   Fri Jul 22 23:25:33 2022 +0300
```

Можно использовать дополнительные параметры, что позволит получить структурированную историю.

Например, просмотр изменений, сделанных за последнюю неделю:
> ```bash=
> git log --all --pretty=format:"%h %cd %s (%an)" --since='7 days ago'
> ```
---

[Дальше к теме "" >](./log.md)