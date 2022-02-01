# A Systematic Mapping Study of Suggested Improvements to Object-Oriented Design Patterns
## Replication Package

This is a replication package containing the raw data and query used in the paper entitled "A Systematic Mapping Study of Suggested Improvements to Object-Oriented Design Patterns".

### Raw data

You can find an Excel spreadsheet of the raw data in the [data.xlsx](https://github.com/wflageol-uqtr/ReplicationPackage-MappingStudy2022/blob/main/data.xlsx) file above.

The spreadsheet has different pages for different views of the data. Here is a summary:

* AllPapers: The secondary studies used in our paper. This list contains the names of the papers and various information about them (e.g. publication venues, publishers, etc.). It also gives each paper a number which is used to reference that particular paper in the other pages.
* Improvements: Details about the various improvements each papers suggested to design patterns, categorized by paradigm.
* MetricsPapers: A table relating every metric to the papers in which it was used.
* MetricsCategories: A table relating every metric to the category it was classified in.
* DesignPatterns: A table relating every design patterns to the papers that addressed them.

### Query

A single query was used in our paper on the Engineering Village search engine. Here is that query:

    ((oop OR object) AND ({design pattern} OR {design patterns} OR {anti-pattern} OR {anti-patterns} OR paradigm) AND (weakness* OR disadvantage* OR improve* OR enhance* OR refine* OR help OR better OR expand*) WN AB) NOT ((teach* OR learn* OR test* OR modeling OR automated OR automation  OR tool* OR mobile OR optimiz* OR simulation OR mining OR medical OR bio* OR hardware OR hdl OR parallel* OR api OR find* OR sql OR {pattern recognition} OR {pattern identification} OR {pattern detection} OR {object recognition} OR {object detection} OR {feature extraction} OR {computer vision} OR {pattern clustering} OR {learning (artificial intelligence)} OR {image segmentation} OR {pattern classification} OR {data mining} OR {computer aided design} OR {formal specification} OR {image classification} OR {user interfaces} OR {computer simulation} OR {internet} OR {image processing} OR {codes (symbols)} OR {image enhancement} OR {embedded systems} OR {image reconstruction} OR {cameras} OR {distributed computer systems} OR {product design} OR {artificial intelligence} OR {iterative methods} OR {neural nets} OR {neural networks} OR {object tracking} OR {genetic algorithms} OR {classification (of information)} OR {learning systems} OR {mathematical models} OR {middleware} OR {internet of things} OR {cloud computing} OR {decision making} OR {electroencephalography} OR {virtual reality} OR {risk management} OR {health care} OR {distributed object management} OR {query processing} OR {knowledge based systems}) WN KY)
    
The results should then be filtered by date between 2000 and 2019.
