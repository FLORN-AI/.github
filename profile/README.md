# Explore your data with FLORN

FLORN explores tabular data on its own, even when you start without a question. It looks for relationships, formulates hypotheses, and tests them against the data. You can also bring your own question or use a new dataset to check whether an earlier finding still holds.

[Try the interactive penguin demo](https://florn.ai/demo/penguins?lang=en) · [Watch the presentation on YouTube](https://www.youtube.com/watch?v=uyEkZUap_GU)

[Explore FLORN](https://florn.ai/) · [Français](https://florn.ai/?lang=fr) · [Polski](https://florn.ai/?lang=pl)

## What can you learn from a table of penguin measurements?

Do penguins with deeper bills tend to weigh more? In the Palmer Penguins dataset, the answer changes when you group the birds by species. Across the 342 birds with both measurements, deeper bills tend to go with **lower** body mass. Within each of the three species, deeper bills tend to go with **higher** body mass.

| Birds compared | Correlation between bill depth and body mass (Spearman) |
| --- | ---: |
| All three species together | −0.43 |
| Adélie | +0.60 |
| Chinstrap | +0.58 |
| Gentoo | +0.76 |

## Check a PDF report against its source data

If you already have a report, FLORN can check its claims against the data you supply. You can see which claims the data support, which they contradict and which remain unresolved.

For example, Broz and colleagues reported two mean cell counts in Figure 3a of a *Nature Communications* paper. The five measurements in each group give means of **45,026.72** and **68,194.48**. Rounded to whole cells, they match the reported **45,027** and **68,194**. The public result shows the workbook cells for both checks. [See the figure, source workbook and verification](https://florn.ai/results/sarcoma-figure-3a)

[Browse more public results](https://florn.ai/results)

FLORN is operated by **H INNOV LLC**. For questions about exploring your data or checking a report, write to [contact@florn.ai](mailto:contact@florn.ai).
