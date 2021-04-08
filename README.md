# Search_Engine
Implementation of an optimised search Engine in python language .

## Steps to generate index 
```python
    pip3 install -r requirements.txt # to install all required packages
    python3 inv_index_generator.py <wikipedia_dump_filepath> <path_to_store_index>
```
## Steps to search 
```python
    python3 search.py <index_location> 
```
## Format of Query 
### Field Query 
<p> 3, t:World Cup i:2019 c:Cricket <br>
2, t:the two towers i:1954 </p>

Each line is of the format  K, QS where K is the number of results to return and QS is the query string. 1<=K<=100

#### For More Information refer to Questions.pdf
