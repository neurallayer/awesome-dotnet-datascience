# Awesome .NET for Data Science, Machine Learning and AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome .Net packages, frameworks and resources for data science, machine learning and AI. 
It is inspired by many of the other awesome pages like awesome-python, awesome-php, awesome-ruby and awesome-dotnet.

Since almost daily new datascience packages for .Net are being released or updated, this is a great place to stay up to date. 


## Interactive Development
* [.NET Interactive](https://github.com/dotnet/interactive) - .NET Interactive takes the power of .NET and embeds it into your interactive experiences. Share code, explore data, write, and learn across your apps in ways you couldn't before. Right now there is support for Jupyter, nteract, and Visual Studio Code.
* [Azure Jupyter Notebooks](https://notebooks.azure.com/) - Jupyter notebooks on Azure have builtin supper for F#.
* [Binder](https://mybinder.org/) - Binder is an online application that allows you to point it to a github repo and start a Jupyter notebook that is in there. Binder supports C#, F# and even Powershell notebooks. And if you just want to try some notebooks right now, click [here](https://mybinder.org/v2/gh/dotnet/interactive/master?urlpath=lab).
* [IfSharp](https://github.com/fsprojects/IfSharp) - F# for Jupyter Notebooks with intellisense and integrated NuGet support.

## Dataframes
* [Microsoft.Data.Analysis](Microsoft.Data.Analysis) - Robust and extensible types and algorithms for manipulating structured data that supports aggregations, statistical funtions, sorting, grouping, joins, merges, handling missing values and more. Currently in preview mode.
* [Deedle](https://bluemountaincapital.github.io/Deedle/) - Data frame and (time) series library for exploratory data manipulation with C# and F# support
* [Pandas.NET](https://github.com/SciSharp/Pandas.NET) - Pandas ported to C#. It is a data analysis tool that can process multi-dimensional arrays using DataFrames.
* [Spreads](https://github.com/Spreads/Spreads/) - Series and Panels for Real-time and Exploratory Analysis of Data Streams. Spreads library is optimized for performance and memory usage. It is several times faster than other open source projects.


## Visualization
* [Plot.NET](https://github.com/SciSharp/Plot.NET) - .NET wrapper of plotly.js for ICSharpCore.
* [XPlot](https://fslab.org/XPlot/) - XPlot is data visualization package for F# and .NET. Uses Plotly and Google Charts as "backends" to render fancy visualization.  

## Big Data
* [.NET for Apache Spark](https://dotnet.microsoft.com/apps/data/spark) - The .NET bindings for Spark are written on the Spark interop layer, designed to provide high performance bindings to multiple languages. .NET for Apache Spark is compliant with .NET Standard—a formal specification of .NET APIs that are common across .NET implementations. This means you can use .NET for Apache Spark anywhere you write .NET code. 
* [Cinchoo ETL](https://github.com/Cinchoo/ChoETL) - Cinchoo ETL is a code-based ETL framework for extracting data from multiple sources, transforming, and loading into your very own data warehouse in .NET environment. 
*[ETLBox](https://etlbox.net/) - Read and write data from flatfiles, databases (e.g. Sql Server, SQLite, MySql or Postgres) or webservices. Harmonize, filter, aggregate, validate and clean the data in-memory with highly customizable transformations and write them into any destination.
*[FsShelter](https://github.com/Prolucid/FsShelter) - FsShelter is a library for defining and running Apache Storm topologies in F# using statically typed streams.

## Data loading
* [F# Data](https://fsharp.github.io/FSharp.Data/) - F# type providers for accessing XML, JSON, CSV and HTML files (based on sample documents) and for accessing WorldBank data.
* [HDF.PInvoke](https://github.com/HDFGroup/HDF.PInvoke) - HDF.PInvoke is a collection of PInvoke signatures for the HDF5 C-API. It is not a high-level .NET interface for HDF5.
* [HDF5-CSharp](https://github.com/LiorBanai/HDF5-CSharp) - Set of tools that help in reading and writing hdf5 files for .net environments.
* [parquet-dotnet](https://github.com/aloneguid/parquet-dotnet) - Fully managed .NET library to read and write Apache Parquet files.
* [Lightning.NET](https://github.com/CoreyKaylor/Lightning.NET) - .NET library for LMDB key-value store. LMDB is a Btree-based database management library. The entire database is exposed in a memory map, and all data fetches return data directly from the mapped memory. As such, the library is extremely high performance and memory-efficient. So ideal for storing large amount of data during machine learning.
* [Json.NET](https://github.com/JamesNK/Newtonsoft.Json) - Serialize and deserialize any .NET object with Json.NET's JSON serializer. 

## Language bindings
* [R Provider](https://bluemountaincapital.github.io/FSharpRProvider/) - Type provider that exposes R packages and functions in a type-safe way to F# callers
* [Python.NET](https://pythonnet.github.io/) - Python.NET is a package that gives Python programmers integration with the .NET 4.0+ Common Language Runtime (CLR). Python.NET provides a powerful application scripting tool for .NET developers. Using this package you can script .NET applications or build entire applications in Python, using .NET services and components written in any language that targets the CLR (C#, VB.NET, F#, C++/CLI).
* [IronPython](https://ironpython.net/) - IronPython is an open-source implementation of the Python programming language which is tightly integrated with the .NET Framework. IronPython can use the .NET Framework and Python libraries, and other .NET languages can use Python code just as easily. 

## Math and Statistics
* [Math.NET Numerics](https://numerics.mathdotnet.com/) - Math.NET Numerics aims to provide methods and algorithms for numerical computations in science, engineering and every day use. Covered topics include special functions, linear algebra, probability models, random numbers, interpolation, integration, regression, optimization problems and more.
* [Math.NET Symbolics](https://symbolics.mathdotnet.com/) - Math.NET Symbolics is a basic open source computer algebra library for .Net and Mono written in F#.
* [Math.NET Filtering](https://filtering.mathdotnet.com/) - Filtering aims to provide a toolkit for digital signal processing, offering an infrastructure for digital filter design, applying those filters to data streams using data converters, as well as digital signal generators.
* [Math.NET Spatial](https://spatial.mathdotnet.com/) - Math.NET Spatial is aiming to become a geometry library for .Net and Mono.
* [NumSharp](https://github.com/SciSharp/NumSharp) - High Performance Computation for N-D Tensors in .NET, similar API to NumPy wrtitten in pure C#.
* [Numpy.NET](https://github.com/SciSharp/Numpy.NET) - Numpy.NET is an almost complete .NET binding for NumPy.
* [ILNumerics](https://ilnumerics.net/index.html) - set of tools for engineers and scientists based on modern software frameworks that help to develop, deploy and maintain technical applications. Consist of development tooling (integrated in Visual Studio), visualization engine and a compute engine.
* [ALGLIB](https://www.alglib.net/) - ALGLIB is a cross-platform numerical analysis and data processing library.  It supports several programming languages (C++, C#, Delphi) and several operating systems (Windows and POSIX, including Linux).


## Computer Vision
* [SharpCV](https://github.com/SciSharp/SharpCV) - A Computer Vision library that combines OpenCV and NDArray together in .NET Standard. Great for processing images and video before feeding into a machine learning model. 
* [OpenCVDotNet](https://code.google.com/archive/p/opencvdotnet) - A wrapper for the OpenCV project to be used with .NET applications.
* [Emgu CV](http://www.emgu.com/wiki/index.php/Main_Page) - Cross platform wrapper of OpenCV which can be compiled in Mono to be run on Windows, Linus, Mac OS X, iOS, and Android.
* [Accord.NET Extensions](https://github.com/dajuric/accord-net-extensions) - Advanced image processing and computer vision algorithms made as fluent extensions.

## Natural Language Processing
* [Stanford.NLP for .NET](https://github.com/sergey-tihon/Stanford.NLP.NET/) - A full port of Stanford NLP packages to .NET and also available precompiled as a NuGet package.
* [Catalyst](https://github.com/curiosity-ai/catalyst) Catalyst is a C# Natural Language Processing library built for speed. Inspired by spaCy's design, it brings pre-trained models, out-of-the box support for training word and document embeddings, and flexible entity recognition models.


## Machine Learning and Differential Programming
* [ML.NET](https://github.com/dotnet/machinelearning) - Cross-platform open-source machine learning framework which makes machine learning accessible to .NET developers. This framework wraps several other libraries and is actively being developed. So a great place to start.
* [SciSharp STACK](https://scisharp.github.io/SciSharp/) - A rich machine learning ecosystem for .NET created by porting the most popular libraries to C#. Since the APIs of the ported libraries are so similar to the originals you can easily re-use all existing resources, documentation and community solutions to common problems in C# or F# without much effort. Severel of their packages are listed separately on this page.
* [Accord.NET](http://accord-framework.net/) - Machine learning framework combined with audio and image processing libraries (computer vision, computer audition, signal processing and statistics). Merged with [AForge.NET](http://www.aforgenet.com/framework/).
* [numl](http://numl.net/index.html) - This library is designed to assist in the use of common Machine Learning Algorithms in conjunction with the .NET platform. It is designed to include the most popular supervised and unsupervised learning algorithms while minimizing the friction involved with creating the predictive models.
* [FsLab](https://fslab.org/) - FsLab is a curated collection of open source F# packages for data-science. Together with your editor or Jupyter notebook these packages allow you to rapidly develop scalable, high-performance analytics and visualizations using succinct, type-safe, production-ready code.
* [Infer.NET](https://dotnet.github.io/infer/) - A framework for running Bayesian inference in graphical models. It can also be used for probabilistic programming.
* [Synapses](https://github.com/mrdimosthenis/Synapses) - An in-memory neural network library written in F#. 
* [Torch.NET](https://github.com/SciSharp/Torch.NET) - .NET bindings for PyTorch. Machine Learning with C# / F# with Multi-GPU/CPU support 
* [TorchSharp](https://github.com/xamarin/TorchSharp) - TorchSharp is a .NET library that provides access to the library that powers PyTorch. It is a work in progress, but already provides a .NET API that can be used to perform (1) various operations on ATen Tensors; (2) scoring of TorchScript models; (3) Training of simple neural networks. Current focus is to bind the entire API surfaced by libtorch.
* [MxNet.Sharp](https://mxnet.tech-quantum.com/) - MxNet.Sharp is a CSharp binding coving all the Imperative, Symbolic and Gluon API’s with an easy to use interface. The Gluon library in Apache MXNet provides a clear, concise, and simple API for deep learning. It makes it easy to prototype, build, and train deep learning models without sacrificing training speed.
* [onxxruntime](https://microsoft.github.io/onnxruntime/) - ONNX Runtime is an open source project that is designed to accelerate machine learning across a wide range of frameworks, operating systems, and hardware platforms. It enables acceleration of machine learning inferencing across all of your deployment targets using a single set of API. Standard binding for C#.
* [Tensorflow.Net](https://github.com/SciSharp/TensorFlow.NET) - .NET Standard bindings for Google's TensorFlow for developing, training and deploying Machine Learning models in C#. 
* [Keras.NET](https://github.com/SciSharp/Keras.NET) - Keras.NET is a high-level neural networks API, written in C# with Python Binding and capable of running on top of TensorFlow, CNTK, or Theano.
* [NeuralNetwork.NET](https://github.com/Sergio0694/NeuralNetwork.NET) - A TensorFlow-inspired neural network library built from scratch in C# 7.3 for .NET Standard 2.0, with GPU support through cuDNN.
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
* [SciSharp Cube](https://github.com/SciSharp/SciSharpCube) - Easy way to get all the latest features of SciSharp Machine Learning tools in docker container.


## Domain specific
* [Lean](https://github.com/QuantConnect/Lean/) - Lean Engine is an open-source algorithmic trading engine built for easy strategy research, backtesting and live trading.
* [QuantAD](https://www.xcelerit.com/products/quantad/) - Automatic Differentiation tool targeted at Quantitative Finance.
* [BotSharp](https://github.com/SciSharp/BotSharp) - BotSharp is an open source machine learning framework for AI Bot platform builder. This project involves natural language understanding, computer vision and audio processing technologies, and aims to promote the development and application of intelligent robot assistants in information systems.


# Contributing
Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/neurallayer/awesome-dotnet-datascience/blob/master/CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could [vote for them](https://github.com/neurallayer/awesome-dotnet-datascience/pulls) by adding :+1: to them. 
