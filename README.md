# i-have-neuro-hub

**A hub of on/off presets that combine three output-style skills: i-have-adhd, i-have-asd and i-have-tbi.**

**i-have-adhd・i-have-asd・i-have-tbi の3つのスキルを組み合わせたプリセットを、オン・オフで持つハブです。**

> **Not medical advice.** This is an output-style skill for AI coding assistants. It is not a diagnosis, a treatment, a therapy, or a medical device, and it has not been clinically tested. No diagnosis is needed to use it.
>
> **医療の助言ではありません。** AI コーディングアシスタントの出力の形を決めるスキルです。診断・治療・療法・医療機器ではなく、臨床で試されたものでもありません。使うのに診断は要りません。

## Status / いまの状態

Work in progress. [SKILL.md](SKILL.md) holds one trial preset, [preset-1-light](docs/presets/preset-1-light.md). It has not been tested yet. The design notes are in [docs/](docs/).

作りかけです。[SKILL.md](SKILL.md) には、試しのプリセット [preset-1-light](docs/presets/preset-1-light.md) が1つ入っています。まだ動かして試していません。設計のメモは [docs/](docs/) にあります。

## What it is / これは何か

Each of the three skills shapes the assistant's output for one kind of reader. Some readers want more than one of them at once, and the three skills' rules can overlap or pull in different directions. The hub is the layer above them: it holds presets, each one a fixed combination of the three skills, and each preset can be turned on or off.

3つのスキルは、それぞれ1つの読み手に合わせてアシスタントの出力を整えます。同時に2つ以上を使いたい読み手もいて、そのとき3つの決まりは重なったり、逆を向いたりします。ハブはその上の層です。3つのスキルの決まった組み合わせをプリセットとして持ち、プリセットごとにオン・オフできます。

The hub does not copy the rules. Each skill's rules live in its own repository.

ハブは決まりを写しません。決まりの本文は、それぞれのスキルのリポジトリにあります。

## The three skills / 3つのスキル

| Skill | Repository |
| --- | --- |
| i-have-adhd | [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) |
| i-have-asd | [hamidasiblog/i-have-asd](https://github.com/hamidasiblog/i-have-asd) |
| i-have-tbi | [hamidasiblog/i-have-tbi](https://github.com/hamidasiblog/i-have-tbi) |

## Acknowledgements / 謝辞

Thanks to Ayoub Ghriss for [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) (MIT). It is the original work: i-have-asd and i-have-tbi are modelled on it, and this hub exists because of it.

[ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)（MIT）を作った Ayoub Ghriss さんに感謝します。i-have-asd と i-have-tbi はこれを手本にしており、このハブもそこから始まっています。

## License / ライセンス

[MIT](LICENSE)
