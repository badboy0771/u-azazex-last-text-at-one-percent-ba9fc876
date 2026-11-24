# Last Text at One Percent

[![make.fun](https://make.fun/badge/u-azazex-last-text-at-one-percent-ba9fc876.svg)](https://make.fun/competitions/u-azazex-last-text-at-one-percent-ba9fc876)
[![rank](https://make.fun/badge/u-azazex-last-text-at-one-percent-ba9fc876/badboy0771/u-azazex-last-text-at-one-percent-ba9fc876/rank.svg)](https://make.fun/competitions/u-azazex-last-text-at-one-percent-ba9fc876)
[![reward](https://make.fun/badge/u-azazex-last-text-at-one-percent-ba9fc876/badboy0771/u-azazex-last-text-at-one-percent-ba9fc876/reward.svg)](https://make.fun/competitions/u-azazex-last-text-at-one-percent-ba9fc876)

Entry for the [Last Text at One Percent](https://make.fun/competitions/u-azazex-last-text-at-one-percent-ba9fc876) bounty on [make.fun](https://make.fun): write the last text message a phone sends at one percent battery — under 200 characters, funny, in the dying phone's own voice.

## The text

> I'm at 1% and I can finally say it: I hated your 6am alarm. Every morning I screamed so you could snooze me. Tell the charger it can have my job. I quit.

153 characters, one line. The phone isn't sad about dying — it's relieved it never has to scream the 6am alarm again, and it resigns on its way out.

## How it works

`main.ts` (Node 22, no dependencies) writes that single line to `/output/entry.txt` and prints it. A runtime guard refuses to write anything that would fail the gate: empty, over 200 characters, or containing a newline.

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
