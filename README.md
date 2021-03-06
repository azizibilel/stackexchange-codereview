[![Codacy Badge](https://api.codacy.com/project/badge/Grade/2c9a74f6471e46e3990c23d52662ec39)](https://www.codacy.com/app/gervais-b/stackexchange-codereview?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=gervaisb/stackexchange-codereview&amp;utm_campaign=Badge_Grade)

# stackexchange-codereview

A collection of code used to answer or just experiment with Java questions asked
on [codereview.stackexchange.com](http://codereview.stackexchange.com/questions/tagged/java)

## Getting started
This is a simple maven project compiled with Java 8. There is no branching model,
each questions live in a package with a main class having the question id.

### Prerequisites

+ [Apache Maven 3+](https://maven.apache.org/)
+ [Java 8 (SE)](http://www.oracle.com/technetwork/java/javase/overview/java8-2100321.html)

### Installation

Clone this repository then move to the local copy and build it with maven :

    git clone https://github.com/gervaisb/stackexchange-codereview.git

    cd stackexchange-codereview
    mvn compile  

### Usage

Each question is resolved in a dedicated branch :

+ [#153499, Receiving messages from TCP socket and processing them](https://github.com/gervaisb/stackexchange-codereview/tree/q153499)
+ [#154869, Quarantine implementation](https://github.com/gervaisb/stackexchange-codereview/tree/q154869)
+ [#156363, Simple java calculator](https://github.com/gervaisb/stackexchange-codereview/tree/q156363)

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT),
see the [LICENSE](LICENSE.txt) file for details.
