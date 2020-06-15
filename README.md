# Awesome .NET Datascience [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome .Net packages, frameworks and resources for datascience. It is inspired by many of the other awesome pages like awesome-php.

Since almost daily new datascience related software for .Net is released or updated, this is a great place to stay up to date. 



## Interactive Development
* [.NET Interactive](https://github.com/dotnet/interactive) - .NET Interactive takes the power of .NET and embeds it into your interactive experiences. Share code, explore data, write, and learn across your apps in ways you couldn't before. Right now there is support for Jupyter, nteract, and Visual Studio Code.

## Dataframes
* [Microsoft.Data.Analysis](Microsoft.Data.Analysis) - Robust and extensible types and algorithms for manipulating structured data that supports aggregations, statistical funtions, sorting, grouping, joins, merges, handling missing values and more. Currently in preview mode.
* [Deedle](https://bluemountaincapital.github.io/Deedle/) - Data frame and (time) series library for exploratory data manipulation with C# and F# support
* [Pandas.NET](https://github.com/SciSharp/Pandas.NET) - Pandas ported to C#. It is a data analysis tool that can process multi-dimensional arrays using DataFrames.


## Visualization
* [Plot.NET](https://github.com/SciSharp/Plot.NET) - .NET wrapper of plotly.js for ICSharpCore.
* [XPlot](https://fslab.org/XPlot/) - XPlot is data visualization package for F# and .NET. Uses Plotly and Google Charts as "backends" to render fancy visualization.  

## Big Data
* [.NET for Apache Spark](https://dotnet.microsoft.com/apps/data/spark) - The .NET bindings for Spark are written on the Spark interop layer, designed to provide high performance bindings to multiple languages. .NET for Apache Spark is compliant with .NET Standard—a formal specification of .NET APIs that are common across .NET implementations. This means you can use .NET for Apache Spark anywhere you write .NET code. 

## Data Connectivity
* [F# Data](https://fsharp.github.io/FSharp.Data/) - F# type providers for accessing XML, JSON, CSV and HTML files (based on sample documents) and for accessing WorldBank data.


## Language bindings
* [R Provider](https://bluemountaincapital.github.io/FSharpRProvider/) - Type provider that exposes R packages and functions in a type-safe way to F# callers
* [Python.NET](https://pythonnet.github.io/) - Python.NET is a package that gives Python programmers integration with the .NET 4.0+ Common Language Runtime (CLR). Python.NET provides a powerful application scripting tool for .NET developers. Using this package you can script .NET applications or build entire applications in Python, using .NET services and components written in any language that targets the CLR (C#, VB.NET, F#, C++/CLI).

## Math and Statistics
* [Math.NET](https://numerics.mathdotnet.com/) - Math.NET Numerics aims to provide methods and algorithms for numerical computations in science, engineering and every day use. Covered topics include special functions, linear algebra, probability models, random numbers, interpolation, integration, regression, optimization problems and more.
* [NumSharp](https://github.com/SciSharp/NumSharp) - High Performance Computation for N-D Tensors in .NET, similar API to NumPy.


## Computer Vision
* [SharpCV](https://github.com/SciSharp/SharpCV) - A Computer Vision library that combines OpenCV and NDArray together in .NET Standard. Great for processing images and video before feeding into a machine learning model. 
* [OpenCVDotNet](https://code.google.com/archive/p/opencvdotnet) - A wrapper for the OpenCV project to be used with .NET applications.
* [Emgu CV](http://www.emgu.com/wiki/index.php/Main_Page) - Cross platform wrapper of OpenCV which can be compiled in Mono to be run on Windows, Linus, Mac OS X, iOS, and Android.
* [AForge.NET](http://www.aforgenet.com/framework/) - Framework for developers and researchers in the fields of Computer Vision and Artificial Intelligence (image processing, neural networks, genetic algorithms, machine learning, robotics).
* [Accord.NET](http://accord-framework.net/) - Machine learning framework combined with audio and image processing libraries (computer vision, computer audition, signal processing and statistics).
* [Accord.NET Extensions](https://github.com/dajuric/accord-net-extensions) - Advanced image processing and computer vision algorithms made as fluent extensions.

## Natural Language Processing
* [Stanford.NLP for .NET](https://github.com/sergey-tihon/Stanford.NLP.NET/) - A full port of Stanford NLP packages to .NET and also available precompiled as a NuGet package.
* [Catalyst](https://github.com/curiosity-ai/catalyst) Cross-platform Natural Language Processing (NLP) library inspired by spaCy, with pre-trained models, out-of-the box support for training word and document embeddings, and flexible entity recognition models.


## Machine Learning and Differential Programming
* [ML.NET](https://github.com/dotnet/machinelearning) - Cross-platform open-source machine learning framework which makes machine learning accessible to .NET developers. This framework wraps several other libraries and is actively being developed. So a great place to start.
* [Infer.NET](https://dotnet.github.io/infer/) - A framework for running Bayesian inference in graphical models. It can also be used for probabilistic programming.
* [numl](http://numl.net/index.html) - This library is designed to assist in the use of common Machine Learning Algorithms in conjunction with the .NET platform. It is designed to include the most popular supervised and unsupervised learning algorithms while minimizing the friction involved with creating the predictive models.
* [FsLab](https://fslab.org/) - A collection of data science and machine learning libraries for F# and .NET
* [Spreads](https://github.com/Spreads/Spreads/) - Series and Panels for Real-time and Exploratory Analysis of Data Streams. Spreads library is optimized for performance and memory usage. It is several times faster than other open source projects.
* [SciSharp STACK](https://scisharp.github.io/SciSharp/) - A rich machine learning ecosystem for .NET created by porting the most popular Python libraries to C#. 
* [Synapses](https://github.com/mrdimosthenis/Synapses) - An in-memory neural network library written in F#. 
* [Torch.NET](https://github.com/SciSharp/Torch.NET) - .NET bindings for PyTorch. Machine Learning with C# / F# with Multi-GPU/CPU support 
* [TorchSharp](https://github.com/xamarin/TorchSharp) - TorchSharp is a .NET library that provides access to the library that powers PyTorch. It is a work in progress, but already provides a .NET API that can be used to perform (1) various operations on ATen Tensors; (2) scoring of TorchScript models; (3) Training of simple neural networks. Current focus is to bind the entire API surfaced by libtorch.
* [MxNet.Sharp](https://mxnet.tech-quantum.com/) - MxNet.Sharp is a CSharp binding coving all the Imperative, Symbolic and Gluon API’s with an easy to use interface. The Gluon library in Apache MXNet provides a clear, concise, and simple API for deep learning. It makes it easy to prototype, build, and train deep learning models without sacrificing training speed.
* [onxxruntime](https://microsoft.github.io/onnxruntime/) - ONNX Runtime is an open source project that is designed to accelerate machine learning across a wide range of frameworks, operating systems, and hardware platforms. It enables acceleration of machine learning inferencing across all of your deployment targets using a single set of API. Standard binding for C#.
* [Tensorflow.Net](https://github.com/SciSharp/TensorFlow.NET) - .NET Standard bindings for Google's TensorFlow for developing, training and deploying Machine Learning models in C#. 
* [Microsoft Cognitive Toolkit (CNTK)](https://docs.microsoft.com/en-us/cognitive-toolkit/) - The Microsoft Cognitive Toolkit (CNTK) is an open-source toolkit for commercial-grade distributed deep learning. It describes neural networks as a series of computational steps via a directed graph. CNTK allows the user to easily realize and combine popular model types such as feed-forward DNNs, convolutional neural networks (CNNs) and recurrent neural networks (RNNs/LSTMs). 
* [XGBoost.Net](https://github.com/PicNet/XGBoost.Net) - .Net wrappers for the awesome XGBoost library
* [DiffSharp](https://diffsharp.github.io/DiffSharp/) - DiffSharp allows for exact and efficient calculation of derivatives, by systematically invoking the chain rule of calculus at the elementary operator level during program execution.
* [autodiff](https://github.com/alexshtf/autodiff) - A .NET library that provides fast, accurate and automatic differentiation (computes derivative / gradient) of mathematical functions.

## Reinforcement Learning
* [Gym.NET](https://github.com/SciSharp/Gym.NET) - A complete port of OpenAI Gym to C#. OpenAI Gym is a toolkit for developing and comparing reinforcement learning algorithms. This is the gym open-source library, which gives you access to a standardized set of environments. Work in progress.
* [Deep QLearning demo](https://github.com/dubezOniner/Deep-QLearning-Demo-csharp) - This demo is a C# port of [ConvNetJS RLDemo](https://cs.stanford.edu/people/karpathy/convnetjs/demo/rldemo.html) by Andrej Karpathy.

## Genetic Programming
* [GeneticSharp](https://github.com/giacomelli/GeneticSharp) - Multi-platform genetic algorithm library for .NET Core and .NET Framework. The library has several implementations of GA operators, like: selection, crossover, mutation, reinsertion and termination.
* [SharpNEAT](https://github.com/colgreen/sharpneat) - SharpNEAT provides an implementation of an Evolutionary Algorithm (EA) with the specific goal of evolving neural networks. The EA uses the evolutionary mechanisms of mutation, recombination and selection to search for neural networks with behaviour that satisfies some formally defined problem.

## Serving

## Domain specific
* [Lean](https://github.com/QuantConnect/Lean/) - Lean Engine is an open-source algorithmic trading engine built for easy strategy research, backtesting and live trading.
* [QuantAD](https://www.xcelerit.com/products/quantad/) - Automatic Differentiation tool targeted at Quantitative Finance


# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/neurallayer/awesome-dotnet-datascience/blob/master/CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could [vote for them](https://github.com/neurallayer/awesome-dotnet-datascience/pulls) by adding :+1: to them. 
