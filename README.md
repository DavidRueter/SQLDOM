# SQLDOM
HTML parser and DOM-related procedures for Microsoft T-SQL

SQLDOM is an easy and robust way to parse HTML directly into SQL tables, manipulate DOM nodes in a JQuery-like manner, and to render HTML from the SQL-based DOM.

SQLDOM is written entirely in native T-SQL, and uses only temporary database objects (tempdb). No changes to user databases are required.

Features:
Screen scraping HTML pages into structured data
Generation of HTML in SQL from templates (i.e. merge templates with data)
HTML checker / LINT-like analysis
Easy node-based search-and-replace
Other HTML analysis in support of optimization
