<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Windows Server 2022 Active Directory Lab</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" rel="stylesheet">

<style>

body{
background:#f5f7fb;
font-family:Segoe UI;
}

.hero{
background:linear-gradient(135deg,#004aad,#001d5e);
color:white;
padding:70px;
}

.section-title{
border-left:6px solid #0d6efd;
padding-left:15px;
margin-top:60px;
margin-bottom:25px;
}

.card{
border:none;
box-shadow:0px 5px 15px rgba(0,0,0,.08);
margin-bottom:25px;
}

pre{
background:#1f2937;
color:white;
padding:15px;
border-radius:8px;
}

footer{
background:#001d5e;
color:white;
padding:30px;
margin-top:60px;
}

.timeline{
border-left:4px solid #0d6efd;
padding-left:25px;
margin-left:20px;
}

.timeline .step{
margin-bottom:35px;
}

code{
color:#ffdd57;
}

</style>

</head>

<body>

<!-- HERO -->

<section class="hero text-center">

<h1 class="display-4">

<i class="fa-solid fa-server"></i>

Windows Server 2022 Active Directory Lab

</h1>

<p class="lead">

Complete Step-by-Step Installation Guide using VMware Workstation

</p>

<a href="#requirements" class="btn btn-light btn-lg mt-3">

Get Started

</a>

</section>

<!-- NAVIGATION -->

<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">

<div class="container">

<a class="navbar-brand" href="#">

AD Lab

</a>

<button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#nav">

<span class="navbar-toggler-icon"></span>

</button>

<div class="collapse navbar-collapse" id="nav">

<ul class="navbar-nav ms-auto">

<li class="nav-item"><a class="nav-link" href="#requirements">Requirements</a></li>

<li class="nav-item"><a class="nav-link" href="#vmware">VMware</a></li>

<li class="nav-item"><a class="nav-link" href="#windows">Windows Server</a></li>

<li class="nav-item"><a class="nav-link" href="#ad">Active Directory</a></li>

<li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>

</ul>

</div>

</div>

</nav>

<div class="container">

<!-- INTRO -->

<div class="card mt-5">

<div class="card-body">

<h3>

<i class="fa-solid fa-circle-info text-primary"></i>

Project Overview

</h3>

<p>

This project demonstrates how to build a complete Windows Server 2022 Active Directory environment inside VMware Workstation.

After completing this guide you will understand virtualization, Windows Server installation, Active Directory, DNS, DHCP, domain management and client integration.

</p>

</div>

</div>

<!-- REQUIREMENTS -->

<h2 id="requirements" class="section-title">

<i class="fa-solid fa-computer"></i>

Phase 1 - Requirements

</h2>

<div class="row">

<div class="col-md-6">

<div class="card">

<div class="card-header bg-primary text-white">

Hardware

</div>

<div class="card-body">

<ul>

<li>Intel Core i5 or Ryzen 5 (64-bit)</li>

<li>Virtualization Enabled (VT-x / AMD-V)</li>

<li>Minimum 8GB RAM (16GB Recommended)</li>

<li>100GB Free Disk Space</li>

<li>Windows 10/11 Host</li>

<li>SSD Recommended</li>

</ul>

</div>

</div>

</div>

<div class="col-md-6">

<div class="card">

<div class="card-header bg-success text-white">

Software

</div>

<div class="card-body">

<ul>

<li>VMware Workstation Pro</li>

<li>Windows Server 2022 ISO</li>

<li>Windows 10 ISO</li>

</ul>

</div>

</div>

</div>

</div>

<!-- TIMELINE -->

<h2 id="vmware" class="section-title">

<i class="fa-solid fa-laptop"></i>

Installation Timeline

</h2>

<div class="timeline">

<div class="step">

<h4>Step 1 - Enable Virtualization</h4>

<ul>

<li>Restart Computer</li>

<li>Enter BIOS</li>

<li>Enable Intel VT-x or AMD-V</li>

<li>Save Changes</li>

</ul>

</div>

<div class="step">

<h4>Step 2 - Install VMware</h4>

<ul>

<li>Download VMware Workstation</li>

<li>Run Installer</li>

<li>Accept License</li>

<li>Finish Installation</li>

</ul>

</div>

<div class="step">

<h4>Step 3 - Create Virtual Machine</h4>

<ul>

<li>Create New VM</li>

<li>Select Windows Server ISO</li>

<li>Assign 4GB RAM</li>

<li>2 CPU Cores</li>

<li>80GB Disk</li>

</ul>

</div>

</div>

<!-- WINDOWS -->

<h2 id="windows" class="section-title">

<i class="fa-brands fa-windows"></i>

Install Windows Server 2022

</h2>

<div class="card">

<div class="card-body">

<ol>

<li>Power On Virtual Machine</li>

<li>Select Language</li>

<li>Install Now</li>

<li>Select Desktop Experience</li>

<li>Create Administrator Password</li>

<li>Restart Server</li>

</ol>

<h5>Administrator Password Example</h5>

<pre>P@ssword123!</pre>

</div>

</div>

<!-- NETWORK -->

<h2 class="section-title">

<i class="fa-solid fa-network-wired"></i>

Configure Static IP

</h2>

<div class="card">

<div class="card-body">

<table class="table table-bordered">

<tr>

<th>Setting</th>

<th>Value</th>

</tr>

<tr>

<td>IP Address</td>

<td>192.168.1.10</td>

</tr>

<tr>

<td>Subnet</td>

<td>255.255.255.0</td>

</tr>

<tr>

<td>Gateway</td>

<td>192.168.1.1</td>

</tr>

<tr>

<td>DNS</td>

<td>192.168.1.10</td>

</tr>

</table>

</div>

</div>

<!-- ACTIVE DIRECTORY -->

<h2 id="ad" class="section-title">

<i class="fa-solid fa-users"></i>

Install Active Directory

</h2>

<div class="card">

<div class="card-body">

<ol>

<li>Open Server Manager</li>

<li>Manage</li>

<li>Add Roles & Features</li>

<li>Select Active Directory Domain Services</li>

<li>Install</li>

<li>Promote Server</li>

<li>Create New Forest</li>

</ol>

<h4>Root Domain</h4>

<pre>company.local</pre>

</div>

</div>

<!-- USERS -->

<h2 class="section-title">

<i class="fa-solid fa-user-group"></i>

Create Organizational Units

</h2>

<div class="card">

<div class="card-body">

<pre>

IT

HR

Finance

Sales

Users

Computers

Servers

</pre>

</div>

</div>

<!-- DNS -->

<h2 class="section-title">

<i class="fa-solid fa-globe"></i>

DNS & DHCP

</h2>

<div class="card">

<div class="card-body">

<ul>

<li>Install DNS</li>

<li>Verify Forward Lookup Zone</li>

<li>Install DHCP</li>

<li>Create Scope</li>

<li>Activate Scope</li>

</ul>

</div>

</div>

<!-- CLIENT -->

<h2 class="section-title">

<i class="fa-solid fa-desktop"></i>

Join Windows Client

</h2>

<div class="card">

<div class="card-body">

<ol>

<li>Create Windows 10 VM</li>

<li>Configure DNS</li>

<li>Join Domain</li>

<li>Restart</li>

<li>Login with Domain User</li>

</ol>

<pre>

COMPANY\jdoe

</pre>

</div>

</div>

<!-- TOPOLOGY -->

<h2 class="section-title">

<i class="fa-solid fa-diagram-project"></i>

Lab Topology

</h2>

<div class="card">

<div class="card-body">

<pre>

Internet

|

Router

192.168.1.1

|

VMware

|

Windows Server 2022

Domain Controller

DNS

DHCP

192.168.1.10

|

Windows 10 Client

Joined to Domain

</pre>

</div>

</div>

<!-- SKILLS -->

<h2 id="skills" class="section-title">

<i class="fa-solid fa-graduation-cap"></i>

Skills Gained

</h2>

<div class="row">

<div class="col-md-4">

<div class="card">

<div class="card-body text-center">

<i class="fa-solid fa-server fa-3x text-primary"></i>

<h5 class="mt-3">Windows Server</h5>

</div>

</div>

</div>

<div class="col-md-4">

<div class="card">

<div class="card-body text-center">

<i class="fa-solid fa-users fa-3x text-success"></i>

<h5 class="mt-3">Active Directory</h5>

</div>

</div>

</div>

<div class="col-md-4">

<div class="card">

<div class="card-body text-center">

<i class="fa-solid fa-network-wired fa-3x text-danger"></i>

<h5 class="mt-3">Networking</h5>

</div>

</div>

</div>

<div class="col-md-4">

<div class="card">

<div class="card-body text-center">

<i class="fa-solid fa-globe fa-3x text-warning"></i>

<h5 class="mt-3">DNS & DHCP</h5>

</div>

</div>

</div>

<div class="col-md-4">

<div class="card">

<div class="card-body text-center">

<i class="fa-solid fa-desktop fa-3x text-info"></i>

<h5 class="mt-3">Virtualization</h5>

</div>

</div>

</div>

<div class="col-md-4">

<div class="card">

<div class="card-body text-center">

<i class="fa-solid fa-user-shield fa-3x text-secondary"></i>

<h5 class="mt-3">Identity Management</h5>

</div>

</div>

</div>

</div>

</div>

<footer class="text-center">

<h4>Windows Server 2022 Active Directory Lab</h4>

<p>

Created for Learning • GitHub Portfolio • Systems Administration • Networking

</p>

</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>

</html>
