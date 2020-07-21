---
layout: page
title: Contact Me
description: Got Something to Say?
background: '/img/bg-contact.jpg'
form: true
---

<p>Want to get in touch? Fill out the form below to send me a message and I will get back to you as soon as possible!</p>
<form name="sentMessage" id="contactForm" name="sentMessage" novalidate action="https://formspree.io/gerryleonugroho@gmail.com" method="POST"> 	
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Nama Anda</label>
      <input type="text" class="form-control" placeholder="Nama" id="name" required data-validation-required-message="Silahkan Masukan Email Anda.">
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Alamat Email</label>
      <input type="email" class="form-control" placeholder="Alamat Email" id="email" required data-validation-required-message="Silahkan Masukan Alamat Email.">
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group col-xs-12 floating-label-form-group controls">
      <label>No Telp/WA</label>
      <input type="tel" class="form-control" placeholder="Nomor Telp" id="phone" required data-validation-required-message="Silahkan Masukan No Telp/WA.">
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Pesan Anda</label>
      <textarea rows="5" class="form-control" placeholder="Pesan Anda" id="Pesan Anda" required data-validation-required-message="Pesan Anda."></textarea>
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <br>
  <div id="success"></div>
  <div class="form-group">
    <button type="submit" class="btn btn-primary" id="sendMessageButton">Kirim</button>
  </div>
</form>
