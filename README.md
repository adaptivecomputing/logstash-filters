# logstash-filters
A collection of grok patters that match applications provided by Adaptive Computing

# Contributing

Contributions are encouraged
Please create a merge request


## Syntax Example

- Name  
- Example log line  
- Grok pattern  
- Tested version  
- Notes   

    Job Submit
    04/04/2014 18:26:34;0040;foo bar
    %{DATE} %{TIME};%{WORD:hostname} %{WORD:command}
    Moab 7.2.7, 7.1.5
    Notes: works with fqdn, doesnt work with.....


#### Disclaimer: 

These logstash filters are a collection of community provided examples,
They are given freely with no guarantee of quality or accuracy
Adaptive Computing does not provide support for any third party utilities
Logstash and Grok are traidmarks of their respective creators