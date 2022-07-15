
+++
date = "2022-05-15T07:12:45+10:00"
draft = false
title = "Code Typeface"
[menu]
  [menu.main]
    name = "Code Typeface"
    parent = "visual"
    identifier = "code-typeface"
    weight = 3
    url = "/visual/code/"
+++

<div class="row text-left">
  <div class="col-xs-12">
    <div class="page-header">
      <a class="page-header--anchor" id="title"></a>
      <a href="#title">
        <h1></h1>
      </a>
    </div>
  </div>
  <div class="col-md-6">
    <h1>Font used for code blocks</h>
    <hr class="teal-line">
    <p class="color-text">Roboto Mono is a monospaced addition to the Roboto type family. Like the other members of the Roboto family, the fonts are optimized for readability on screens across a wide variety of devices and reading environments. While the monospaced version is related to its variable width cousin, it doesn’t hesitate to change forms to better fit the constraints of a monospaced environment. For example, narrow glyphs like ‘I’, ‘l’ and ‘i’ have added serifs for more even texture while wider glyphs are adjusted for weight. Curved caps like ‘C’ and ‘O’ take on the straighter sides from Roboto Condensed.<br/>
    (Source: <a href="https://fonts.google.com/specimen/Roboto+Mono#about" target="_blank">Google Fonts</a>)</p>       
  </div>
  <div class="col-md-6">
    <div class="row">
        <h2>Roboto Mono</h2>
        </br></br>
          <h3>Characters</h3>
          <hr class="teal-line">
          <p class="code upper-case">abcdefghijklmnopqrstuvwxyz</p>
          <p class="code lowercase-case">abcdefghijklmnopqrstuvwxyz</p>
          <p class="code lowercase-case">‘ ? ’ “ ! ” ( % ) [ # ] { @ } / & \ < - + ÷ × = > ® © $ € £ ¥ ¢ : ; , . *</p>
          </br></br>
          <h3>Example</h3>
         <hr class="teal-line">
            <p class="code">
                from influxdb_client import InfluxDBClient
                url = 'https://us-west-2-1.aws.cloud2.influxdata.com'
                token = 'my-token'
                org = 'my-org'
                bucket = 'my-bucket'
                with InfluxDBClient(url=url, token=token, org=org) as client:
                    query_api = client.query_api()
                    tables = query_api.query('from(bucket: "my-bucket") |> range(start: -1d)')
                    for table in tables:
                        for record in table.records:
                            print(str(record["_time"]) + " - " + record.get_measurement()
                                + " " + record.get_field() + "=" + str(record.get_value()))
            </p>
    </div>
  </div>
</div>