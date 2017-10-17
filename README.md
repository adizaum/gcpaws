<!DOCTYPE html>
<html lang="en">

<head>
    <title>Cloud Compare: AWS vs. GCP</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>

<style type="text/css">
    html, body {
      height:100%;
      margin:0;
      font: 400 15px/1.8 "Lato", sans-serif;
      color: #777;
    }
    .bigimg-1{
      background-image: "http://www.texturepalace.com/wp-content/uploads/pretty-clouds-17.jpg"
      height:100%;
    }
    .footer{
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      background-color: #efefef;
      text-align: center;
    }
</style>

  <div class="w3-center">
  <h4 >Cloud Comparison</h4>
  <i class="fa fa-cloud" style="font-size:24px;"></i>
  <h1 class="w3-xxxlarge w3-animate-bottom">GCP vs. AWS</h1>
  <img src="https://media.tenor.com/images/9189da1a3c593a70e08a2988ad948112/tenor.gif" alt="Smiley face" height="200" width="250">
 
  <br>

  <nav class="w3-bar w3-light-grey">
  <div class="w3-bar-item w3-hover-blue" onclick="openSolution('Compute')">Compute</div>
  <div class="w3-bar-item w3-hover-red" onclick="openSolution('Storage')">Storage</div>
  <div class="w3-bar-item w3-hover-yellow" onclick="openSolution('BigData')">Big Data</div>
  <div class="w3-bar-item w3-hover-blue" onclick="openSolution('Networking')">Networking</div>
</nav>


<div id="Compute" class="w3-container solution w3-animate-left">
  <h2>Compute</h2>
  <table class="w3-table-all w3-card-4" style="width:100%; padding: 90px">
  <tr>
    <th>Category</th>
    <th>Feature</th> 
    <th><img class="img-responsive" src="http://d3fe8kjw89mk6u.cloudfront.net/sites/default/files/inline-images/Amazon-Web-Services-2-min.jpg" height="50" alt="icon"></th>
    
    <th><img class="img-responsive" src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTJyS1clPIUc2NQ6DDlLI9VXs-_Bck40_j5G3ekSo2cnydNHwQn" height="50" alt="icon"></th>
  </tr>
  <tr>
     <td><a href="https://cloud.google.com/docs/compare/aws/compute">Compute</a>
      <td>IaaS<br>PaaS<br>VM<br>Machine images<br>Temporary VM<br>Firewall<br>Firewall<br>Automatic instance scaling<br>Local attached disk<br>Local attached disk<br>Discounts</td>
      <td>EC2<br>Elastic Beanstalk<br>Elastic Compute Cloud Container<br>ServiceInstances<br>Amazon MachineImage<br>Spotinstances<br>Securitygroups<br>Manual/Scheduled/Dynamic autoscaling (group)<br>Ephemeral disk<br>Supported formats: RAW, OVA, VMDK, and VHD<br>reserved instances</td>
      <td>GCE<br>GAE<br>GKE<br>Instances<br>Image<br>Preemptible VMs<br>Compute Engine firewall rules<br>Dynamic autoscaler (managed instance group)<br>Local SSD<br>Supported formats: RAW<br>sustained-use discount (-30%)</td>
  </tr>
</table>
</div><br>
     

  <div id="Storage" class="w3-container solution w3-animate-left" style="display:none">
  <h2>Storage</h2>
  <table class="w3-table-all w3-card-4" style="width:100%; padding: 90px">
  <tr>
    <th>Category</th>
    <th>Feature</th> 
    <th><img class="img-responsive" src="http://d3fe8kjw89mk6u.cloudfront.net/sites/default/files/inline-images/Amazon-Web-Services-2-min.jpg" height="50" alt="icon"></th>
    <th><img class="img-responsive" src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTJyS1clPIUc2NQ6DDlLI9VXs-_Bck40_j5G3ekSo2cnydNHwQn" height="50" alt="icon"></th>
  </tr>

  <tr>
    <td><a href="https://cloud.google.com/docs/compare/aws/storage">Storage</a></td>
    
    <td>
      Object Storage<br>Block Storage<br>Cold Storage<br>File Storage<br>Unit of deployment<br>Deployment identifier<br>File system emulation<br>Object metadata<br>Object versioning<br>Object lifecycle management<br>Update notifications<br>Service classes<br>Deployment locality<br>Price
      <br><br> RDBMS<br> NoSQL: Key-value<br> NoSQL: Indexed<br> Batch Data Processing<br> Stream Data Processing<br> Open source library<br> Service integration<br> Scaling<br> Deployment locality<br> Pricing model<br> Unit of Deployment<br> Unit of Scale<br> Unit of Work<br> Programming Model<br>Customization
    </td>
    <td>
      S3<br>Elastic Block Store<br>Glacier<br>Elastic File System<br>Bucket<br>Globally unique key<br>Limited<br>Yes<br>Yes<br>Yes<br>Event notifications<br>Standard, Reduced Redundancy, Infrequent Access, Amazon Glacier<br>Regional<br>S3 RRS - data stored/month, network egress, API requests, data retrieval per-GB basis<br><br> RDSDynamoDB<br>SimpleDB<br>Elastic MapReduce<br>Kinesis<br>Hadoop, Spark<br>Yes<br>Manual<br>Zonal<br>Per-hour<br>Cluster<br>Nodes (Master, Core and Task)<br>Step<br>MapReduce, Hive, Pig, Spark, Spark SQL, PySpark<br>Bootstrap actions<br>
    </td>
    <td>
      Cloud Storage<br>Compute Engine Persistent Disks<br>Cloud Storage Nearline<br>ZFS / Avere<br>Bucket<br>Globally unique key<br>Limited<br>Yes<br>Yes<br>Yes<br>Object change notifications<br>Standard, Durable Reduced Availability, Nearline<br>Regional and multi-regional<br>Storage DRA - data stored/month, network egress, API request<br><br> Cloud SQL<br>Datastore, Bigtable<br>Datastore<br>Dataproc / Dataflow<br>Dataflow<br>Hadoop, Spark / Beam<br>Yes / Yes<br>Manual / Auto<br>Zonal<br>Per-second / Per-min<br>Cluster / Pipeline<br>Nodes (Master and Worker) / Workers<br>Job<br>MapReduce, Hive, Pig, Spark, Spark SQL, PySpark / Beam<br>Initialization actions / File staging<br>
    </td>
  </tr>
  </table>
</div>

<div id="BigData" class="w3-container solution w3-animate-left" style="display:none">
  <h2>Big Data</h2>
  <table class="w3-table-all w3-card-4" style="width:100%; padding: 90px">
  <tr>
    <th>Category</th>
    <th>Feature</th> 
    <th><img class="img-responsive" src="http://d3fe8kjw89mk6u.cloudfront.net/sites/default/files/inline-images/Amazon-Web-Services-2-min.jpg" height="50" alt="icon"></th>
    <th><img class="img-responsive" src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTJyS1clPIUc2NQ6DDlLI9VXs-_Bck40_j5G3ekSo2cnydNHwQn" height="50" alt="icon"></th>
  </tr>

  <tr>
    <td><a href="https://cloud.google.com/docs/compare/aws/big-data">Big Data</a></td>
    <td>Analytics<br>Unit of deployment<br>Unit of provisioning<br>Node Types<br>Scaling<br>Backup management<br>Deployment locality<br>Pricing model<br>Query language<br><br>Stream Data Ingest<br>Unit of Deployment<br>Unit of Provisioning<br>Data Unit<br>Data Source<br>Data Destination<br>Data Partitioning<br>Retention Period<br>Data Delivery Order<br>Max Data Size<br>Deployment Locality<br>Pricing Model<br>
    </td>
    <td>Redshift<br>Cluster<br>Node<br>Spinning disk / SSD<br>Manual<br>Snapshots<br>Zonal<br>Hourly<br>PostgreSQL compatible<br><br>Kinesis<br>Stream<br>Shard<br>Record<br>Producers<br>Consumer<br>User-supplied partition key<br>1 – 7 days<br>Service-supplied sequence key (best effort)<br>1MB<br>Regional<br>Per shard-hour, per number of operations, and per length of data retention<br>
    </td>
    <td>BigQuery<br>N/A (fully managed)<br>N/A (fully managed)<br>N/A (fully managed)<br>Automatically adjusted<br>N/A (fully managed)<br>Regional<br>By storage and query volume<br>Legacy BigQuery SQL or Standard SQL (Beta)<br><br>Pub/Sub<br>Topic<br>N/A (fully managed)<br>Message<br>Publisher<br>Subscriber<br>N/A (fully managed)<br>7 days<br>Service-supplied publishTime (best effort)<br>10MB<br>Global<br>Per number of operations<br>
    </td>
  </tr>
  </table>
</div>

<div id="Networking" class="w3-container solution w3-animate-left" style="display:none">
  <h2>Networking</h2>
  <table class="w3-table-all w3-card-4" style="width:100%; padding: 90px ">
  <tr>
    <th>Category</th>
    <th>Feature</th> 
    <th><img class="img-responsive" src="http://d3fe8kjw89mk6u.cloudfront.net/sites/default/files/inline-images/Amazon-Web-Services-2-min.jpg" height="50" alt="icon"></th>
    <th><img class="img-responsive" src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTJyS1clPIUc2NQ6DDlLI9VXs-_Bck40_j5G3ekSo2cnydNHwQn" height="50" alt="icon"></th>
  </tr>
  <tr>
    <td><a href="https://cloud.google.com/docs/compare/aws/networking"> Networking</a></td>
    <td>Load Balancer<br>Network load balancing<br>Support for static IP address<br>Content-based load balancing<br>Cross-region load balancing<br>Scaling pattern<br>Deployment locality<br><br>Virtual private network<br>Carrier peering<br>Direct peering<br>CDN peering<br><br>Domain name servers<br>Zone<br>Support for most DNS record types<br>Anycast-based serving<br>Domain registrar<br>Latency-based routing<br>Geography-based routing<br>DNSSEC<br>
    </td>
    <td>Amazon ELB<br>Yes<br>No<br>No<br>No<br>Linear<br>Regional<br><br>VPC-VPN<br>Direct Connect<br>N/A<br>N/A<br><br>Route 53<br>Hosted zone<br>Yes<br>Yes<br>Yes<br>Yes<br>Yes<br>No<br>
    </td>
    <td>GCE Load Balancing<br>Yes<br>Yes<br>Yes<br>Yes<br>Real-time<br>Global<br><br>Cloud VPN<br>Carrier Interconnect<br>Direct Peering<br>CDN Interconnect<br><br>Cloud DNS<br>Managed zone<br>Yes<br>Yes<br>Yes<br>No<br>No<br>No<br><br>
    </td>
  </tr>
  </div>
</table>


<script>
  function openSolution(solutionName) {
    var i;
    var x = document.getElementsByClassName("solution");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    document.getElementById(solutionName).style.display = "block";  
  }
</script>

</body>
</html>
