# Neural-Networks-With-ML.NET

<p align="center">
  <img src="https://github.com/VsIG-official/Neural-Networks-With-ML.NET/blob/master/Images/NeuralNetworks.jpg" data-canonical-src="https://github.com/VsIG-official/Neural-Networks-With-ML.NET/blob/master/Images/NeuralNetworks.jpg"/>
</p>

## Table of Contents

- [Description](#description)
- [Badges](#badges)
- [Contributing](#contributing)
- [Neural Networks](#networks)
- [License](#license)

### Description

Once upon a time I was working on an [AI with My teammates, which was able to identify music's mood](https://github.com/mezidia/song-helper). Now I want to create wome more, but with CSharp and .NET Interactive Notebooks

## Badges

[![Theme](https://img.shields.io/badge/Theme-AI-blueviolet?style=flat-square)](https://www.google.com.ua/)
[![Platform](https://img.shields.io/badge/Platform-CSharp-blueviolet?style=flat-square)](https://www.google.com.ua/)

---

## Networks

- Penguins:
  - [Source](https://rubikscode.net/2021/09/27/net-interactive-jupyter-notebooks/)
  - [Implamentation](https://github.com/VsIG-official/Neural-Networks-With-ML.NET/tree/master/Penguins)
- > Another

## Example

```csharp
var mlContext = new MLContext();

IDataView trainingDataView = mlContext.Data.
LoadFromTextFile<PalmerPenguinsData>("data\\penguins.csv",
hasHeader: true, separatorChar: ',');

DataOperationsCatalog.TrainTestData dataSplit =
mlContext.Data.TrainTestSplit(trainingDataView, testFraction: 0.3);
```

---

## Contributing

> To get started...

### Step 1

- 🍴 Fork this repo!

### Step 2

- **HACK AWAY!** 🔨🔨🔨

---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2021 © <a href="https://github.com/VsIG-official" target="_blank">VsIG</a>.
