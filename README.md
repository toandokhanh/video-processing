- video: duong dan hoac ten file video
- language: ngon ngu lua chon de xuat subtitle
- step_time: buoc nhay de cat audio ra de xuat text tu audio
- noise: chon thuat toan giam nhieu (noise, deep)
- summary: chon thuat toan tom tat van ban (lexrank, textrank, lsa, luhn, random, reduction, edmundson, kl)
- sentence: so dong mong muon tom tat
```
python3 recognize_final.py -l vi -video d.mp4 -noise deep -summary lexrank -sentence 2
```

