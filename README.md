# Random-Sentence-Generator

# 🧠 Random Sentence Generator in python 随机句子生成器

A Python project that takes a **verb** and a **subject word** from the user, and generates a grammatically structured English sentence using simple grammar rules and random elements.  
一个 Python 项目，用户输入一个**动词**和一个**主语**，程序会根据语法规则随机生成一个英文句子。

## How to Run    运行方式  
python main.py

## First Step: input a verb. 输入一个动词

Please input a simple verb, like "walk" "talk" "do" "fly"... The code will find the matched object.  
请输入简单的动词，程序会根据此动词找到合适的宾语

**If the verb is too hard for the code, the code will continuously print sentences structures.**  
如果此动词过于复杂，程序会持续输出句子模板，因为它找不到合适的宾语


## Second Step: imput a word or name. 输入一个单词或名字
It could be a name or anything. This word will be the subject of the sentence.  此词将成为句子的主语  
Then the code will randomly generate a sentence.  随机的句子将会生成并输出

## Sentence Structures:

pronoun verb Noun (preposition Noun)*n  
句子模板为：主语 + 谓语 + （宾语）+ (介词短语）*n

## Example: 

input: eat, Hank

output: Hank eat  an apple in the yard

## 🙏 Acknowledgements 特别鸣谢 
Thanks for the Department of Linguistics and the Institute for Advanced Computational Science (IACS) at Stony Brook University  
Thanks for my mentor Logan

