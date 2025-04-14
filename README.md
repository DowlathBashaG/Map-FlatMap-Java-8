# Map-FlatMap-Java-8

map :
====

map() method used for transformation.

map() takes Stream<T>  as input and return Stream<R>

Its mapper function produces a single value for each input value. Hence it is also called One-To-One mapping.
                                                                                      

Data Transformation in Map :
===========================

Stream.of("a","b","c","d");    ===>  [ A, B, C, D ]  Transform data from lower case to upper case.

                                                                                        

flatMap() :[readme.md](https://github.com/user-attachments/files/19736546/readme.md)

=========

flatMap() used for transformation & falttering.

flatMap() -> map() + flattering

flatMap() takes Stream<Stream<T>> as input and return Stream<R>

Its mapper function produces multiple values for each input value. Hence it is also called One-To-Many mapping.
                                                                                          
Data Transformation in flatMap :
===============================

[[1,2],[3,4],[5,6],[7,8]]    ===>  [1,2,3,4,5,6,7,8]  Convert stream of stream into single stream.




