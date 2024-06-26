# ExcelJS

[![Tests](https://github.com/hyperliskdev/exceljs/actions/workflows/tests.yml/badge.svg?branch=master)](https://github.com/hyperliskdev/exceljs/actions/workflows/tests.yml)


This project was forked from [ExcelJS](https://github.com/exceljs/exceljs). After using some of the functions with ExcelJS, I found some problems with how things were being rendered. To improve this project, I plan to use the [ECMA-376](https://ecma-international.org/publications-and-standards/standards/ecma-376/) standard to include as many of the important XML definitions.

# Installation
```shell
npm install @hyperliskdev/exceljs
```

# Future Features

- Table Data embedded in the `Excel.Table` object.

# Dev Guide

Here is an outline of everything I personally understand about the project and important references that I used.

### Excel Files

Firstly, Excel Files are essentilly just a zip file with XML files containing the proper information. 
