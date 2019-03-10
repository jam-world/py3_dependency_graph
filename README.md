
# Table of Contents

1.  [What is this tool for?](#org504d1e6)
2.  [Usage](#org70a7c56)
    1.  [Requirement](#org632a91b)
    2.  [Install the tool](#org369133b)
    3.  [use case](#orgdefa063)



<a id="org504d1e6"></a>

# What is this tool for?

  This is just a simple python static dependency generate tool, It can help you generate the dependency graph
find circular import.


<a id="org70a7c56"></a>

# Usage


<a id="org632a91b"></a>

## Requirement

You will need the git and graphiz for the tool

    apt-get update
    apt-get install git graphiz-dev


<a id="org369133b"></a>

## Install the tool

    pip install SDGraph


<a id="orgdefa063"></a>

## use case

    SDGraph -f a.py -o dot -n output_name

