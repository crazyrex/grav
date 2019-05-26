---
title: 'User Login'
slug: user-login
process:
    markdown: true
    twig: true
webpushtitle: 'User Login'
webpushurl: 'http://localhost/grav/en/user-login'
webpushbutton:
    send: false
navbar_class: 'navbar-dark bg-inverse'
form:
    name: login
    action: null
    method: post
    fields:
        -
            name: username
            id: username
            type: text
            placeholder: Username
            autofocus: true
            classes: 'form-control form-control-lg'
        -
            name: password
            id: password
            type: password
            placeholder: Password
            classes: 'form-control form-control-lg'
---

