# 🌪️ WindForecastFramework

> An open-source framework for developing probabilistic wind forecasting models using deep learning, designed to integrate with wind farm control systems.

<div align="center">

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Contributors](https://img.shields.io/github/contributors/WindForecastFramework/wind-forecasting)](https://github.com/orgs/WindForecastFramework/people)

</div>

## 🔍 Overview

WindForecastFramework provides a sophisticated platform for developing, tuning, training, and evaluating state-of-the-art deep learning models for probabilistic wind forecasting. Our framework handles complex temporal dependencies in wind farm operational data and integrates seamlessly with downstream control systems.

## 📦 Repositories

Our framework consists of these interconnected repositories:

| Repository | Description |
|------------|-------------|
| [wind-forecasting](https://github.com/WindForecastFramework/wind-forecasting) | 🚀 **Main Application** - Core forecasting framework with data preprocessing, training pipelines, and evaluation tools |
| [pytorch-transformer-ts](https://github.com/WindForecastFramework/pytorch-transformer-ts) | 🧠 **Model Implementation** - Implemented time series transformer models for time series forecasting (forked) |
| [gluonts](https://github.com/WindForecastFramework/gluonts) | 📊 **Base Time Series Library** - Customized fork of GluonTS for probabilistic time series modeling |
| [wind-hybrid-open-controller](https://github.com/WindForecastFramework/wind-hybrid-open-controller) | 🎮 **Downstream Application** - Wind farm control system that consumes forecasts |

## 🌟 Key Features

- 📈 **Probabilistic Forecasting**: Generate probabilistic forecasts with uncertainty estimation
- 🔄 **Multiple Architectures**: Support for various transformer-based models for time-series forecasting in pytorch
- 🖥️ **Distributed Training**: Scale from local development to HPC environments
- 🧪 **Hyperparameter Optimization**: Distributed optimization across multiple GPUs
- 🔗 **Control Integration**: Seamless connection with wind farm control systems

## 👥 Developers

<table>
  <tr>
    <td align="center"><a href="https://github.com/achenry"><img src="https://github.com/achenry.png" width="100px;" alt=""/><br /><sub><b>Aoife Henry</b></sub></a></td>
    <td align="center"><a href="https://github.com/boujuan"><img src="https://github.com/boujuan.png" width="100px;" alt=""/><br /><sub><b>Juan Boullosa</b></sub></a></td>
  </tr>
</table>

## 📄 License

This project is licensed under the [MIT License](LICENSE) - see the individual repositories for specific details.

## 🔗 Related Resources

- TODO: Add documentation and links to pages/repository docs

---

<div align="center">
  <sub>Built with ❤️ for renewable energy research and operations</sub>
</div>
