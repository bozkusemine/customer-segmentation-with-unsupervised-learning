<h2><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif"><span style="color:#8e44ad"><strong>Customer Segmentation via K-Means &amp; Hierarchical Clustering &amp; DBSCAN</strong></span></span></h2>

<p><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">Customer segmentation is the process of dividing a customer base into smaller groups based on common characteristics or behaviors. This is often done as a way to better understand and target specific segments of a customer base, in order to tailor marketing efforts or product offerings to their specific needs and preferences.</span></p>

<p><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">Unsupervised learning is a type of machine learning that involves training a model to find patterns or relationships in data without the use of labeled examples or prior knowledge. It is often used for tasks such as clustering, where the goal is to group data points into clusters based on their similarity to one another. There are several unsupervised learning algorithms that can be used for customer segmentation, including:</span></p>

<ol>
	<li>
	<p><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">K-means clustering: This algorithm divides the data into a specified number of clusters based on the distance between the data points and their respective cluster centroids.</span></p>
	</li>
	<li>
	<p><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">Hierarchical clustering: This algorithm creates a hierarchy of clusters by repeatedly merging or splitting the data based on their similarity.</span></p>
	</li>
	<li>
	<p><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">DBSCAN (Density-Based Spatial Clustering of Applications with Noise): This algorithm divides the data into clusters based on the density of the points and the distance between them.</span></p>
	</li>
</ol>

<h2><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif"><span style="color:#8e44ad"><strong>Business Problem: Segmentation of a Customer Portfolio</strong></span></span></h2>

<p><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">FLO wants to segment its customers and determine marketing strategies according to these segments. To this end, the behaviors of the customers will be defined and groups will be formed according to the clusters in these behaviors.</span></p>

<h2><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif"><span style="color:#8e44ad"><strong>Dataset Story: Purchasing Behavior of FLO Customers</strong></span></span></h2>

<p><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">The dataset includes Flo&#39;s last purchases from OmniChannel (both online and offline shoppers) in 2020 - 2021. 12 Variables 19,945 Observations 2.7MB</span></p>

<ul>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">master_id: Unique client number</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">order_channel: Which channel of the shopping platform is used (Android, ios, Desktop, Mobile)</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">last_order_channel: The channel where the last purchase was made</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">first_order_date: The date of the first purchase made by the customer</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">last_order_date: The date of the customer&#39;s last purchase</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">last_order_date_online: The date of the last purchase made by the customer on the online platform</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">last_order_date_offline: The date of the last purchase made by the customer on the offline platform</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">order_num_total_ever_online: The total number of purchases made by the customer on the online platform</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">order_num_total_ever_offline: Total number of purchases made by the customer offline</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">customer_value_total_ever_offline: The total price paid by the customer for offline purchases</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">customer_value_total_ever_online: The total price paid by the customer for their online shopping</span></li>
	<li><span style="font-family:Lucida Sans Unicode,Lucida Grande,sans-serif">interested_in_categories_12: List of categories the customer has purchased from in the last 12 months</span></li>
</ul>
