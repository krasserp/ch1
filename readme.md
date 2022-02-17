## Task

Produce a JSON report (`output.json`) of data collected via an online survey.

## Deliverable

JavaScript that takes the inputs `data/rawData.json` and `data/dataMap.json` to produce the output below:

```
[{
    title: 'Gender',
    data: {
        Male: 0.49,
        Female: 0.51
    }
},
{
  title: 'Animals seen',
  data: {
      Cat: 0.33,
      Dog: 0.3,
      Donkey: 0.32,
      Elephant: 0.26,
      Aligator: 0.24
  }  
},
{
    title: 'Favorite Animal',
    data: {
        Cat: 0.15,
        Dog: 0.19,
        Donkey: 0.28,
        Elephant: 0.21,
        Aligator: 0.17
    }
}
];
```

**Provide your solution as a public GitHub repository**

**Note**: type `single` questions like `q1 && q3` only have one data point reference in the `rawData.json`  e.g.:`q3= 1 || 2 || 3 || 4 || 5`. Type `multiple` questions have one (boolean `0||1`) data point entry in the `rawData.json` per possible answer option `q2r1=0||1; q2r2=0||1; q2r3=0||1; q2r4=0||1; q2r5=0||1`

For the report(`output.json`) only `q1,q2,q3` are needed.
