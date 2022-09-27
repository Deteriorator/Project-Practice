# Project-Practice
项目实战

- 安装 docutils
  
  .. code-block:: shell

    pip install docutils, pygments
    

- 使用 buildhtml 批量生成 html

  .. code-block:: shell

    python buildhtml.py --writer=html5 --config=docutils.conf .

  或 

  .. code-block:: shell
    
    python buildhtml.py --toc-top-backlinks --writer=html5 --config=docutils.conf .


- 使用 rst2html5 生成单个 html

  .. code-block:: shell

    python [完整路径]rst2html5.py -stg xxx.rst xxx.html

如果对 css 样式不满意可进行自定义， 我已经对 table caption 和 figure caption 进行了\
自定义， 使其居中显示并字体是正常的 (``font-style: normal;``)， 不是斜体 \
(``font-style: italic;``)
