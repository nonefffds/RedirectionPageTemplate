# A thought on using json

Fetch json contents

For i=links then

If type=normal then

document.write("<button type="button" class="btn btn-default btn-lg btn-block btn-light" onclick="location.href=links[0].link”>links[0].title</button>")

If type=pic then

        <button type="button" class="btn btn-default btn-lg btn-block btn-light" data-toggle="modal" data-target="#pop-modal[2]“>links[2].title</button>


        <div class="modal fade" id="pop-modal">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-body bgc">
                <img src=links[2].link alt="" class="img-fluid mx-auto d-block" width="75%" />
              </div>
              <div class="modal-footer bgc">
                <button type="button" class="btn btn-default btn-lg btn-block btn-light" data-dismiss="modal">Close</button>
              </div>
            </div>
          </div>
        </div>
