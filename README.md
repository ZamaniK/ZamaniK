## About Me
I'm a passionate software developer with a focus on creating innovative and user-friendly applications. I have experience in various programming languages and technologies, including but not limited to Java, Python, JavaScript, and HTML/CSS.

In my journey as a developer, I have worked on projects ranging from web development to mobile applications. I enjoy tackling complex problems and finding efficient solutions through logical thinking and continuous learning.

Apart from coding, I also have a keen interest in software architecture, design patterns, and agile methodologies. I believe in the power of collaboration and enjoy working with like-minded developers who share a passion for creating impactful software solutions.

If you're interested in collaborating on projects or have any exciting opportunities, feel free to reach out to me. I'm open to discussing ideas, sharing knowledge, and building great software together!

## Contact Me
- 📞 Contact Number: (+27) 73 740 6704
- 📧 Email Address: Zamanikat100@gmail.com



## Tool Stacks

<canvas id="toolStackChart"></canvas>

<!-- Include the Chart.js library -->
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<!-- Your JavaScript code here -->
<script>
  // JavaScript code from step 3
  <script>
  // Get the canvas element
  var toolStackChart = document.getElementById('toolStackChart').getContext('2d');

  // Define the data for the donut chart
  var donutChartData = {
    labels: ['C# ASP.NET MVC', 'Python', 'Java', 'JavaScript', 'Others'],
    datasets: [
      {
        data: [50, 20, 10, 15, 5],
        backgroundColor: ['#FF6384', '#36A2EB', '#FFCE56', '#4BC0C0', '#E7E9ED']
      }
    ]
  };

  // Configure the options for the donut chart
  var donutChartOptions = {
    responsive: true,
    maintainAspectRatio: false
  };

  // Create the donut chart
  new Chart(toolStackChart, {
    type: 'doughnut',
    data: donutChartData,
    options: donutChartOptions
  });

  // Define the data for the bar chart
  var barChartData = {
    labels: ['C# ASP.NET MVC', 'Python', 'Java', 'JavaScript', 'Others'],
    datasets: [
      {
        label: 'Tool Stacks',
        data: [50, 20, 10, 15, 5],
        backgroundColor: '#4BC0C0'
      }
    ]
  };

  // Configure the options for the bar chart
  var barChartOptions = {
    responsive: true,
    maintainAspectRatio: false,
    scales: {
      y: {
        beginAtZero: true
      }
    }
  };

  // Create the bar chart
  new Chart(toolStackChart, {
    type: 'bar',
    data: barChartData,
    options: barChartOptions
  });
</script>
</script>

<!---
ZamaniK/ZamaniK is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
