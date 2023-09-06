# StudyThree
该文件实现了使用three.js实现引用obj文件模型，并添加事件进行边框高亮显示

使用前请先到three.JS官网下载所需文件，如在使用引用的文件时，控制台报以下错误：Uncaught TypeError: Failed to resolve module specifier "three.js". Relative references must start with either "/", "./", or "../".

需要到引用的文件中第一句 import...from three 这里，将three修改为../../../build/three.module.js（找到自己文件路径下的three.module.js）
