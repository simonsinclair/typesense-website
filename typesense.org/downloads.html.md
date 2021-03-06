---
layout: page
title: Download Typesense
nav_label: downloads
permalink: /downloads/
---

<div class="row no-gutters">
  <div id="doc-col" class="col-md-8">
    <p>Below are the available binaries for the latest version of Typesense: <code>{{ site.versions[0] }}</code></p>
    <p>Please download the appropriate archive for your operating system and architecture.</p>
    <dl id="release-downloads">
      <dt>Linux (X86_64)</dt> <br />

      <div class="row">
        <div class="col-md-2">
          <a href="https://dl.typesense.org/releases/{{ site.versions[0] }}/typesense-server-{{ site.versions[0] }}-amd64.deb">DEB</a>
        </div>

        <div class="col-md-2">
          <a href="https://dl.typesense.org/releases/{{ site.versions[0] }}/typesense-server-{{ site.versions[0] }}-1.x86_64.rpm">RPM</a>
        </div>

        <div class="col-md-2">
          <a href="https://dl.typesense.org/releases/{{ site.versions[0] }}/typesense-server-{{ site.versions[0] }}-linux-amd64.tar.gz">Binary</a>
        </div>
      </div>

      <dt>macOS</dt><br />

      <dd>
        <a href="https://dl.typesense.org/releases/{{ site.versions[0] }}/typesense-server-{{ site.versions[0] }}-darwin-amd64.tar.gz">Binary</a>
      </dd>

      <dt>Docker</dt><br />
      <dd><code>docker pull typesense/typesense:{{ site.versions[0] }}</code></dd>
    </dl>
  </div>
</div>