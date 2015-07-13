---
layout: page
title: "联系我"
description: ""
header-img: "img/contactme-bg.jpg"
---

<p>如有需要，请填写下面的表单并提交，我会尽快与你联系。当然我相信，通过微博、微信或GitHub将会是更有效的沟通方式。（^ V ^）</p>

<form name="sentMessage" id="contactForm" novalidate>
    <div class="row control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>姓名</label>
            <input type="text" class="form-control" placeholder="在这里输入姓名" id="name" required data-validation-required-message="请输入姓名或者昵称.">
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <div class="row control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>邮箱</label>
            <input type="email" class="form-control" placeholder="在这里输入电邮" id="email" required data-validation-required-message="请输入电子邮箱.">
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <div class="row control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>手机</label>
            <input type="tel" class="form-control" placeholder="在这里输入手机" id="phone" required data-validation-required-message="请输入手机号码（仅支持中国大陆运营商）.">
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <div class="row control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>留言</label>
            <textarea rows="5" class="form-control" placeholder="留言可以写在这里" id="message" required data-validation-required-message="请输入您的留言."></textarea>
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <br>
    <div id="success"></div>
    <div class="row">
        <div class="form-group col-xs-12">
            <button type="submit" class="btn btn-default">提交信息</button>
        </div>
    </div>
</form>