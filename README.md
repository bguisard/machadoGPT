# Machado GPT

Work in progress. The goal of this project is to train a GPT model on the
complete works of Machado de Assis, a Brazilian writer.

## Dataset

Machado de Assis' work is available in the public domain[^1]. For this project I
concatenated all of his short stories (contos) and novels (romances) into large
plain text files, named `machadinhoContos.txt` and `machadinhoRomances.txt`. For
convenience, there is also `machadinho.txt`, which concatenates both datasets.

The text has not been preprocessed or altered in any significant way, other than
the removal of the table of contents for each of his stories.

[^1]: https://machado.mec.gov.br/
