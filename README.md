# Neural-Networks-With-ML.NET

<p align="center">
  <img src="https://github.com/VsIG-official/Neural-Networks-With-ML.NET/blob/master/Images/NeuralNetworks.jpg" data-canonical-src="https://github.com/VsIG-official/Neural-Networks-With-ML.NET/blob/master/Images/NeuralNetworks.jpg" width="200" height="100" />
</p>

## Table of Contents

- [Description](#description)
- [Badges](#badges)
- [Contributing](#contributing)
- [License](#license)

### Description

> Subtitle or Short Description Goes Here

## Badges

[![Build Status](http://img.shields.io/travis/badges/badgerbadgerbadger.svg?style=flat-square)](https://travis-ci.org/badges/badgerbadgerbadger) [![Dependency Status](http://img.shields.io/gemnasium/badges/badgerbadgerbadger.svg?style=flat-square)](https://gemnasium.com/badges/badgerbadgerbadger) [![Gem Version](http://img.shields.io/gem/v/badgerbadgerbadger.svg?style=flat-square)](https://rubygems.org/gems/badgerbadgerbadger) [![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org) [![Badges](http://img.shields.io/:badges-9/9-ff6799.svg?style=flat-square)](https://github.com/badges/badgerbadgerbadger)

---

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
