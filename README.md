# isye6740---homework-1---solved
**TO GET THIS SOLUTION VISIT:** [ISYE6740 – Homework 1   – Solved](https://mantutor.com/product/isye6740-homework-1-solved-4/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;84612&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISYE6740 -  Homework 1 &nbsp; -  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Concept questions [30 points]

Please provide a brief answer to each question.

<ol>
<li>(5 points) What’s the main difference between supervised and unsupervised learning?</li>
<li>(5 points) Will different initializations for k-means lead to different results?</li>
<li>(5 points) Give a short proof (can be in words but using correct logic) why k-means algorithm will converge in finite number of iterations.</li>
<li>(5 points) What is the main difference between k-means and generalized k-means algorithm? Explain how the choice of the similarity/dissimilarity/distance will impact the result.</li>
<li>(10 points) Consider the following simple graph</li>
</ol>
Write down the graph Laplacian matrix and find the eigenvectors associated with the zero eigenvalue. Explain how do you find out the number of disconnected clusters in graph and identify these disconnected clusters using these eigenvectors.

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Image compression using clustering [40 points]</h1>
In this programming assignment, you are going to apply clustering algorithms for image compression. Your task is to implement <em>K-means </em>for this purpose. <strong>It is required you implement the algorithms yourself rather than calling k-means from a package. However, it is ok to use standard packages for supplementary tasks, e.g. file i/o, linear algebra, and visualization.</strong>

<strong>Formatting instruction</strong>

As a starting point, we suggest the following input/output signature for your k-means algorithm.

<h2>Input</h2>
pixels: the input image representation. Each row contains one data point (pixel). For image dataset, it contains 3 columns, each column corresponding to Red, Green, and Blue component. Each component has an integer value between 0 and 255. k: the number of desired clusters.

<h2>Output</h2>
class: cluster assignment of each data point in pixels. The assignment should be 1, 2, 3, etc. For <em>k </em>= 5, for example, each cell of class should be either 1, 2, 3, 4, or 5. The output should be a column vector with size(pixels, 1) elements.

centroid: location of <em>k </em>centroids (or representatives) in your result. With images, each centroid corresponds to the representative color of each cluster. The output should be a matrix with <em>K </em>rows and 3 columns. The range of values should be [0, 255], possibly floating point numbers.

<h2>Note</h2>
You may see errors caused by empty clusters when you use too large <em>k</em>. Your implementation should treat this exception as well. That is, do not terminate even if you have an empty cluster, but automatically decrement to a smaller number of clusters.

We recommend you to test your code with several different pictures so that you can detect some problems that might happen occasionally.

If we detect plagarism from any other student’s code or from the web, you will not be eligible for any credit for the entire homework, not just for this problem.

<h1>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Political blogs dataset [30 points]</h1>
We will study a political blogs dataset first compiled for the paper Lada A. Adamic and Natalie Glance, “The political blogosphere and the 2004 US Election”, in Proceedings of the WWW-2005 Workshop on the Weblogging Ecosystem (2005). It is assumed that blog-site with the same political orientation are more likely to link to each other, thus, forming a “community” or “cluster” in a graph. In this question, we will see whether or not this hypothesis is likely to be true based on data.

The dataset nodes.txt contains a graph with <em>n </em>= 1490 vertices (“nodes”) corresponding to political blogs.

The dataset edges.txt contains edges between the vertices. You may remove isolated nodes (nodes that are not connected any other nodes) in the pre-processing.

We will treat the network as an undirected graph; thus, when constructing the adjacency matrix, make it symmetrical by, e.g., set the entry in the adjacency matrix to be one whether there is an edge between the two nodes (in either direction).

In addition, each vertex has a 0-1 label (in the 3rd column of the data file) corresponding to the true political orientation of that blog. We will consider this as the true label and check whether spectral clustering will cluster nodes with the same political orientation as possible.

<ol>
<li>(15 points) Use spectral clustering to find the <em>k </em>= 2<em>,</em>5<em>,</em>10<em>,</em>20 clusters in the network of political blogs (each node is a blog, and their edges are defined in the file txt). Find majority labels in each cluster, for different <em>k </em>values, respectively. For example, if there are <em>k </em>= 2 clusters, and their labels are {0<em>,</em>1<em>,</em>1<em>,</em>1} and {0<em>,</em>0<em>,</em>1} then the majority label for the first cluster is 1 and for the second cluster is 0. <strong>It is required you implement the algorithms yourself rather than calling from a package.</strong></li>
</ol>
Now compare the majority label with the individual labels in each cluster, and report the <em>mismatch rate </em>for each cluster, when <em>k </em>= 2<em>,</em>5<em>,</em>10<em>,</em>20. For instance, in the example above, the mismatch rate for the first cluster is 1/4 (only the first node differs from the majority) and the the second cluster is 1/3.

<ol start="2">
<li>(15 points) Tune your <em>k </em>and find the number of clusters to achieve a reasonably small <em>mismatch rate</em>. Please explain how you tune <em>k </em>and what is the achieved mismatch rate. Please explain intuitively what this results tells about the network community structure.</li>
</ol>
<h1>4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (Bonus Question) Math of k-means clustering [5 points]</h1>
Given <em>m </em>data points x<em><sup>i</sup></em>, <em>i </em>= 1<em>,…,m</em>, <em>K</em>-means clustering algorithm groups them into <em>k </em>clusters by minimizing the distortion function over {<em>r<sup>ij</sup>,µ<sup>j</sup></em>}

<em>m&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; k</em>

<em>J </em>= XX<em>r</em><em>ij</em>∥x<em>i </em>− <em>µ</em><em>j</em>∥2<em>,&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>(1)

<em>i</em>=1 <em>j</em>=1

where <em>r<sup>ij </sup></em>= 1 if x<em><sup>i </sup></em>belongs to the <em>j</em>-th cluster and <em>r<sup>ij </sup></em>= 0 otherwise.

<ol>
<li>(3 points) Derive mathematically that using the squared Euclidean distance ∥x<em><sup>i </sup></em>− <em>µ<sup>j</sup></em>∥<sup>2 </sup>as the dissimilarity function, the centroid that minimizes the distortion function <em>J </em>for given assignments <em>r<sup>ij </sup></em>are given by</li>
</ol>
<em>.</em>

That is, <em>µ<sup>j </sup></em>is the center of <em>j</em>-th cluster.

Hint: You may start by taking the partial derivative of <em>J </em>with respect to <em>µ<sup>j</sup></em>, with <em>r<sup>ij </sup></em>fixed.

<ol start="2">
<li>(2 points) Derive mathematically what should be the assignment variables <em>r<sup>ij </sup></em>be to minimize the distortion function <em>J</em>, when the centroids <em>µ<sup>j </sup></em>are fixed.</li>
</ol>
