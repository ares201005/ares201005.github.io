---
title: "Zhang Lab - Software"
layout: gridlay
excerpt: "Zhang Lab -- Software"
sitemap: false
permalink: /software/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

<b> Academic Software Development </b>

1. <a href="https://github.com/lanl/OpenMS">OpenMS</a> (under active development): Universal/Scalable multiscale ecosystem for solving coupled Maxwell-Schr\"odinger equations in open quantum environments. Current features include 1) FDTD solver for Maxwell equation, 2) QED quantum chemistry solvers (to be released), 3) Modular design for enhanced portability and extension, 4) different backends (Numpy, torch, TiledArray). Features under development include 1) Multiscale QED solvers, 2) Quantum transport, and 3) Quantum dynamics. 

1. <a href="">QubitChem</a> (to be released): a collection of quantum algorithms for quantum chemistry.

1. <a href="https://github.com/ares201005/phd.git">PHD</a>:  Code for Plasmonic Hot-carrier Dissipative Dynamics. It can calculate hot-carrier generation from plasmon decay, the effective temperature of hot-carriers, and dissipative dynamics of plasmonic hot-carriers via electron-electron and electron-phonon scattering. 

1. <a href="https://github.com/ares201005/dolphin">DOLPHIN</a>: A multi-physics finite-element solver for ion transport. Poisson-Nernst-Planck and Navier-Stokes equations are implemented.

1. <a href="http://yangtze.hku.hk/home/software.php">LODESTAR</a> (developed by Prof. Guanhua Chen's group at The University of Hong Kong): A quantum chemistry software package that implements the first-principles method and non-equilibrium Green's function technique for electronic structure, optical response, (time-dependent) quantum transport, and dissipation. The software is designed for the simulation of emerging electronics. My contributions include geometry optimization, time-dependent (dissipative) quantum transport, quantum transport with scattering, solar cell modeling, k-point sampling for supercells, fast algorithms, massively parallelization, etc.

1. <a href="https://github.com/lanl/NEXMD">NEXMD</a>: Nonadiabatic Excited State Molecular Dynamics Software developed at Los Alamos National Laboratory. My contributions include the open-shell method, nonadiabatic molecular dynamics for strong light-matter interaction, and interface with DFTB+.

1. <a href="https://github.com/lanl/LATTE">LATTE</a>: Open source density functional tight binding molecular dynamics code developed at Los Alamos National Laboratory.

1. <a href="https://github.com/lanl/bml">BML</a>: a collection of various matrix data formats (dense and sparse) and their associated algorithms for basic matrix operations.

1. <a href="https://github.com/lanl/qmd-progress">QMD-PROGRESS</a>: Parallel, Rapid O(N) and Graph-based Recursive Electronic Structure Solver. Written in Fortran.

<!--
{% for res in site.data.softwarelist %}

{% if res.highlight == 1 %}

<div class="row">

<div class="col-sm-12 clearfix">
 <div class="well">
  <h4><b>{{ res.title }}</b></h4>
  <h5> {{ res.short }}</h5>
  <img src="{{ site.url }}{{ site.baseurl }}/images/slider/{{ res.image }}" class="img-responsive" width="45%" style="float: left" />
  <p>{{ res.description }}</p>
  <p>{{ res.description2 }}</p>
 </div>
</div>

</div>

{% endif %}
{% endfor %}
-->

<p> &nbsp; </p>





