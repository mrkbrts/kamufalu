# kamufalu 🏘️🪵🐖
A kamufalu egy nem létező magyar falunév generátor, melynek az alapját a Google TensorFlow LSTM[[1]](https://www.tensorflow.org/text/tutorials/text_generation)[[2]](https://keras.io/examples/generative/lstm_character_level_text_generation/) modellje adja.

# Technikai információk 👨🏻‍💻
- A **main.ipynb**-ben van a lényeg. 😉
- Mivel ez egy kísérleti projekt, az algoritmus közel sem tökéletes. További optimalizásra szorul, hiszen jelenlegi formájában ki kell halászni a jól hangzó szavakat az eredményből.

# Források 🗃️
- A "faluneveklistaja.txt" a fő corpus, mely [ezen](https://hu.wikipedia.org/wiki/Magyarország_települései:_A,_Á) a Wikipédia oldalon alapul. Viszont ez közel sem bizonyul teljesenek.
- A "hatarontuli_lista.txt" tovább bővíti ezt határontúli települések magyar neveivel. Forrása az [adatbank.ro](https://sebok2.adatbank.ro).
- A "leggyakoribb_magyar_szavak.txt" tovább magyarosítja a corpus-t, mellyel javul a modell teljesítménye. Forrása [ez](https://en.wiktionary.org/wiki/Wiktionary:Frequency_lists/Hungarian_frequency_list_1-10000) a Wikipédia cikk.

# Jogi bla-bla 👨🏻‍⚖️
Használd, módosítsd, írj hozzá, törölj belőle. De nevezd meg az eredeti projektet, a [@kamufalu](https://twitter.com/kamufalu) twitter oldalát vagy [ezt](https://github.com/mrkbrts/kamufalu) a GitHub oldalt, amin most vagy. Köszi! ❤️
