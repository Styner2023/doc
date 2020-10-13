# FAQ for aiXcoder 2.0

#### What are the new major changes in aiXcoder 2.0?

1. The "Code Completion Engine" runs entirely locally, without uploading code, and the prediction speed is greatly improved;
2. Due to the use of state-of-the-art model compression technology, aiXcoder 2.0 can run smoothly on the CPU;
3. A brand-new deep learning model is adopted to further improve the accuracy;

#### What programming languages do aiXcoder 2.0 support? Which IDEs are supported?

Currently, aiXcoder 2.0 supports the Java language, and other languages (such as Python, JavaScript, TypeScript, C/C++, PHP, Go) will be gradually launched in the near future. When new programming language support is released, we will update the installation and usage documentation.

Correspondingly, aiXcoder2.0 Personal Edition currently supports IntelliJ IDEA, and other IDEs or editors will be launched one after another.

Currently, the operating systems supported by aiXcoder 2.0 include: Windows, MacOS, and Linux.

#### With aiXcoder 2.0 being released, why __No Need To Upload Code__?

We have made major technological innovations to the code completion engine of aiXcoder. Using advanced deep neural network model compression and inference technology, the inference speed of model is faster enough to run on CPU. 

Therefore, aiXcoder 2.0 can be fully deployed on a local computer, there is no need to upload code anymore. 

#### Why can't I immediately see the prediction of "code completion" after installing aiXcoder 2.0?

The code completion inference engine of the aiXcoder 2.0 is deployed locally. When a developer opens a project in the IDE, the relevant files of the project need to be loaded into the inference engine, which usually takes several seconds to ten seconds. At this time, aiXcoder will also give corresponding prompts in IDE's status information bar.

After the above loading process has been done, the developer can use aiXcoder normally. If you have further questions, you can send feedback through the project "[issue-tracker](https://github.com/aixcoder-plugin/issue-tracker)".

