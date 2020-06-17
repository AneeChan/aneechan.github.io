<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


<div class="panel panel-default" style="border-right: 0px; border-left: 0px; border-bottom: 0px;">
  <div class="panel-heading" style="padding: 0px; background-image: none;">
    <div class="navbar navbar-inverse" style="margin-bottom: 0px; border: 0px; border-radius: 15px;">
      <span class="navbar-brand">New Notes</span>
      <a  class="navbar-brand" href="#" style="float: right;"><span class="glyphicon glyphicon-arrow-right"></span></a>
    </div>
  </div>
  <div class="panel-body" style="padding-left: 5px; padding-right: 5px;">
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
      <div class="carousel-inner">
        <div class="item active">
          <div class="thumbnail" style="border-radius: 15px; background-color: #333333">
            <img src="assets/picture/tugas1.jpg" style="border-radius: 15px;">
            <div class="caption">
              <h4 id="kotak_mobile1"></h4>
              <div class="well well-sm" style="margin-bottom: 0px; border-radius: 15px;">
                <div class="row" align="center">
                  <div class="col-xs-6">
                    <a href="#" class="btn btn-danger">Read Me<span class="glyphicon glyphicon-eye-open" style="margin-left: 5px;"></span></a>
                  </div>
                  <div class="col-xs-6">
                    <a data-parent="#accordion" data-toggle="collapse" href="#collapseKesatu" class="btn btn-primary">Info<span class="glyphicon glyphicon-sort" style="margin-left: 5px;"></span></a>
                  </div>
                </div>
              </div>
              <div class="panel-collapse collapse" id="collapseKesatu">
                <div class="panel-body" style="padding: 0px; margin-top: 10px;">
                  <div class="well well-sm" style="margin-bottom: 0px; border-radius: 15px;">
                    <div class="table-responsive">
                      <table class="table" style="margin-bottom: 0px;">
                        <tr><td>Date</td><td>14 Decs 2000</td></tr>
                        <tr><td>Tittle</td><td>Tugas Kalkulus Mencari Luas Fungsi yang Dibatasi</td></tr>
                        <tr><td>Author</td><td>Rivaldo</td></tr>
                      </table>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="thumbnail" style="border-radius: 15px; background-color: #333333;">
            <img src="assets/picture/sample-cover.jpg" style="border-radius: 15px;">
            <div class="caption">
              <h4 id="kotak_mobile1"></h4>
              <div class="well well-sm" style="margin-bottom: 0px; border-radius: 15px;">
                <div class="row" align="center">
                  <div class="col-xs-6">
                    <a href="#" class="btn btn-danger">Read Me<span class="glyphicon glyphicon-eye-open" style="margin-left: 5px;"></span></a>
                  </div>
                  <div class="col-xs-6">
                    <a data-parent="#accordion" data-toggle="collapse" href="#collapseKedua" class="btn btn-primary">Info<span class="glyphicon glyphicon-sort" style="margin-left: 5px;"></span></a>
                  </div>
                </div>
              </div>
              <div class="panel-collapse collapse" id="collapseKedua">
                <div class="panel-body" style="padding: 0px; margin-top: 10px;">
                  <div class="well well-sm" style="margin-bottom: 0px; border-radius: 15px;">
                    <div class="table-responsive">
                      <table class="table" style="margin-bottom: 0px;">
                        <tr><td>Date</td><td></td></tr>
                        <tr><td>Tittle</td><td></td></tr>
                        <tr><td>Author</td><td></td></tr>
                      </table>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="thumbnail" style="border-radius: 15px; background-color: #333333">
            <img src="assets/picture/sample-cover.jpg" style="border-radius: 15px;">
            <div class="caption">
              <h4 id="kotak_mobile1"></h4>
              <div class="well well-sm" style="margin-bottom: 0px; border-radius: 15px;">
                <div class="row" align="center">
                  <div class="col-xs-6">
                    <a href="#" class="btn btn-danger">Read Me<span class="glyphicon glyphicon-eye-open" style="margin-left: 5px;"></span></a>
                  </div>
                  <div class="col-xs-6">
                    <a data-parent="#accordion" data-toggle="collapse" href="#collapseKetiga" class="btn btn-primary">Info<span class="glyphicon glyphicon-sort" style="margin-left: 5px;"></span></a>
                  </div>
                </div>
              </div>
              <div class="panel-collapse collapse" id="collapseKetiga">
                <div class="panel-body" style="padding: 0px; margin-top: 10px;">
                  <div class="well well-sm" style="margin-bottom: 0px; border-radius: 15px;">
                    <div class="table-responsive">
                      <table class="table" style="margin-bottom: 0px;">
                        <tr><td>Date</td><td></td></tr>
                        <tr><td>Tittle</td><td></td></tr>
                        <tr><td>Author</td><td></td></tr>
                      </table>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <a class="left carousel-control" style="background-image: none;" href="#myCarousel" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" style="background-image: none;" href="#myCarousel" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</div>
