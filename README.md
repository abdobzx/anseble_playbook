

<h1>Ansible Playbook for Building Containers</h1>

<p>This repository contains an Ansible playbook (<code>ansible-playbook.yml</code>) that automates the process of building and managing containers for a mini project. The playbook performs the following tasks:</p>

<ol>
    <li>🛑 Stop any existing container named <code>abdobz-web-site</code>.</li>
    <li>🗑️ Remove the container <code>abdobz-web-site</code>, if it exists.</li>
    <li>🗑️ Remove the Docker image <code>web-site</code>, if it exists.</li>
    <li>🏗️ Build a new Docker image named <code>web-site</code>.</li>
    <li>▶️ Run a new container named <code>abdobz-web-site</code> from the <code>web-site</code> image, exposing it on port <code>8087</code>.</li>
</ol>

<h2>How to Use</h2>

<p>To execute the Ansible playbook, follow these steps:</p>

<ol>
    <li>Make sure you have Ansible installed on your local machine.</li>
    <li>Place the <code>ansible-playbook.yml</code> file in the root directory of your project.</li>
    <li>Open a terminal and navigate to the directory containing the <code>ansible-playbook.yml</code> file.</li>
    <li>Run the following command:</li>
</ol>

<pre><code>ansible-playbook ansible-playbook.yml</code></pre>

<p>This will execute the playbook, automating the container building process.</p>

<h2>Contributing</h2>

<p>We welcome contributions to this repository! If you have ideas for additional automation scripts or improvements, please feel free to open an issue or submit a pull request. 🚀</p>

<h2>Future Enhancements</h2>

<p>In the future, we plan to expand this repository with more automation scripts and playbooks to help people automate various tasks using Ansible. 🌟</p>

</body>
</html>
