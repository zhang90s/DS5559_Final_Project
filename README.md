# DS5559 Exploratory Text Analytics - Romantic British Novels

<p align="center">
  <img src="https://github.com/zhang90s/DS5559_Final_Project/blob/master/book_img.jpg" width="880" title="book image">
</p>

([Image Source](https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwjZwY2GkYDiAhVxkuAKHYgPBPIQjRx6BAgBEAU&url=http%3A%2F%2Falena-vysotskaya.ru%2Fbooks-backgrounds%2Fimg8918996D7B&psig=AOvVaw0ipnQd9dZ9529tkfWTpJwO&ust=1556999391114791 "image source"))

## Team
- Mengyao Zhang (mz6jv)
- Runhao Zhao (rz6dg)

## Corpus

This GitHub repo contains the code for analyzing 30 British novels with a romantic theme mainly from the 19th century. The following table shows the novels and authors for our corpus.

book_num | title | author | publication_year*
---------| ------| ------- | ---------------
1|Jane Eyre|Charlotte Bronte|1847
2|Shirley|Charlotte Bronte|1849
3|Villette|Charlotte Bronte|1853
4|The Professor|Charlotte Bronte|1857
5|Wuthering Heights|Emily Bronte|1847
6|Agnes Grey|Anne Bronte|1847
7|The Tenant of Wildfell Hall|Anne Bronte|1848
8|Persuasion|Jane Austen|1817
9|Northanger Abby|Jane Austen|1817
10|Mansfield Park|Jane Austen|1814
11|Emma|Jane Austen|1815
12|Pride and Prejudice|Jane Austen|1813
13|Sense and Sensibility|Jane Austen|1811
14|North and South|Elizabeth Cleghorn Gaskell|1855
15|Wives and Daughters|Elizabeth Cleghorn Gaskell|1866
16|Middlemarch|George Eliot|1872
17|The Mill on the Floss|George Eliot|1860
18|Adam Bede|George Eliot|1859
19|Lady Anna|Anthony Trollope|1874
20|Cecilia|Frances Burney|1782
21|Can You Forgive Her|Anthony Trollope|1865
22|Doctor Thorne|Anthony Trollope|1858
23|Miss Mackenzie|Anthony Trollope|1865
24|Rachel Ray|Anthony Trollope|1863
25|The Claverings|Anthony Trollope|1867
26|The Way We Live Now|Anthony Trollope|1875
27|David Copperfield|Charles Dickens|1850
28|Great Expectations|Charles Dickens|1861
29|Little Dorrit|Charles Dickens|1857
30|Our Mutual Friend|Charles Dickens|1865

\* *If book was published in series, use the last year.*

## File Description
The follow table shows the description for each file for this project. For the files uploaded to UVA BOX, you can find them within the [ETA_Project_British_Novels folder](https://virginia.app.box.com/folder/72268721511 "ETA_Project_British_Novels folder"). 

<p align="left">
  <img src="https://github.com/zhang90s/DS5559_Final_Project/blob/master/readme_new.PNG" width="750" height="800 title="hover text">
</p>
                                                                                                                               
## Flask App
We developed a flask app showing the PCA and t-SNE plots using chapters as the documents. For both plots, author_ids were used as the label for the documents. A screenshot of the app is shown below. 
* For the PCA plot, the user is able to enter the number of principal components and the two components to be visualized. The plot will be displayed on the Home tab. 
* For the t-SNE plot, the plot is shown directly on the TSNE tab.

<p align="center">
  <img src="https://github.com/zhang90s/DS5559_Final_Project/blob/master/flask_screenshot.png" title="flask screenshot">
</p>

## Polo2
We also utilized [polo2](https://github.com/ontoligent-design/polo2 "polo2 link") to explore the topic models for 9 novels (one for each author) using chapters as documents. The corpus was reduced due to constraint of computational power. Below represents a screenshot of the web app after running polo2.

<p align="center">
  <img src="https://github.com/zhang90s/DS5559_Final_Project/blob/master/polo2_screenshot.png" title="polo2 screenshot">
</p>                                                                                                                                   
