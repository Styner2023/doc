# FAQ for aiXcoder 2.0

#### What are the new major changes in aiXcoder 2.0?

1. The "Code Completion Engine" runs entirely locally, without uploading code, and the prediction speed is greatly improved;
2. Due to the use of state-of-the-art model compression technology, aiXcoder 2.0 can run smoothly on CPU;
3. A brand-new deep learning model is adopted to further improve the accuracy;

#### What programming languages does aiXcoder 2.0 support? Which IDEs are supported?

Currently, aiXcoder 2.0 supports Java and Python. Supports for other languages, such as JavaScript, TypeScript, C/C++, PHP and Go, will be gradually implemented in the near future. When new programming language support is released, we will update the installation and usage documentation.

Correspondingly, aiXcoder2.0 Personal Edition currently supports IntelliJ IDEA and PyCharm. Other IDEs or editors' support will be released soon.

The operating systems supported by aiXcoder 2.0 include: Windows, MacOS, and Linux.

#### With aiXcoder 2.0 being released, why __No Need To Upload Code__?

We have made major technological innovations to the code completion engine of aiXcoder. Using advanced deep neural network model compression and inference technology, model inference is faster enough to run on CPU. 

Therefore, aiXcoder 2.0 can be fully deployed on a local machine, there is no need to upload code anymore. 

#### Why can't I immediately see the prediction of "code completion" after installing aiXcoder 2.0?

The code completion inference engine of the aiXcoder 2.0 is deployed locally. When a project is opened in the IDE, the relevant files of the project need to be loaded into the inference engine, which usually takes several to ten seconds. During this time, aiXcoder will still give prompts in IDE's status information bar by falling back to the IDE's suggestions.

After the loading process has been done, the developer can use aiXcoder normally. 

If you have further questions, please send feedback through "[issue-tracker](https://github.com/aixcoder-plugin/issue-tracker)".

