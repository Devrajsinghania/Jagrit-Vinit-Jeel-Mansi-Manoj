
<div align=center>

<h2> Feasibility Study report - Smart Search  </h2>
</div>

## Overview of Document

The Feasibility Study report covers economic and technical feasibility of the application.


## Analysis of problem (Why do we need this software?)

As we all know that many times we find problem searching a particular topic within a book on the other hand we can directly jump to the topic and more than that many people face problem when they encounter books in scanned format i.e. jpegs and png.

In this digitized mode of learning(e-learning) almost all of us use soft-copies suggested by friends, teachers and others for learning or reading. All the time searching the content inside the scanned documents is very difficult as search is not supported in images. Only the name of the image can be queried but not the content carried by the image.
And also most of the times we want a particular concept/topic, and we download the whole book but end up not understanding or founding it not useful.

##### We surveyed, belonging to different diverse sectors like Educational Institutions (teachers/professors), students, book-lovers and general public.


#### 1.
![](https://cloud.githubusercontent.com/assets/16951071/18737515/fdb435b4-80af-11e6-8629-b1b9a5133df6.PNG)




#### 2.
![](https://cloud.githubusercontent.com/assets/16951071/18737516/fdb5baa6-80af-11e6-8ddd-2c50999e13b1.PNG)




#### 3.

![](https://cloud.githubusercontent.com/assets/16951071/18737517/fdb8ade2-80af-11e6-9ea3-ae85e40e9089.PNG)


Solution:

So, the application we develop addresses the above problems in this way as follows:
- We upload the scanned documents and using OCR (Optical Character Recognition) extract the content (text) out of it.
- We use this json format files to feed Elastic Search and make the documents searchable.
- If user searches for any concept/topic/book/notes the most relevant suggestion is shown along with the reviews of the document.
- User can view/download the document if it is useful(scanned original document).
Also, user can create personal libraries out of the documents which are useful.


## Limitations and Constraints

- Internet connection and a web browser to access the application independent of the device.
- Only one language support i.e. English User
- The application is built keeping in mind the user has basic knowledge in using Web Applications.
- The application produce result based on the database, so its robustness to query depends on the size and dimension of database.


## Economic Feasibility
The application is developed using all open-source softwares/libraies on Linux (Ubuntu). The developers will be making this available freely for anyone to download and reuse under GNU General Public License V3.


## Conclusions From Our Survey

