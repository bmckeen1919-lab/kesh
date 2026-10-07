# Kesh

A generated language (`conlang` toolkit), translating *The Quiet Morning*.

## Regenerate

    conlang generate --spec spec/kesh.yaml --out out/kesh.json

## Translate

    conlang translate --workspace . --glosses the_quiet_morning_kesh.tsv \
      --sentences the_quiet_morning_sentences.csv --out the_quiet_morning_kesh.csv
    conlang validate-translation --csv the_quiet_morning_kesh.csv
