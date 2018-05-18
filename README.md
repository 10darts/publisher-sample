# publisher-sample

Example of client web using a redirection.

[Go to the demo](https://10darts.github.io/web-subscription-sample/)

We add at the bottom of the page the code to show the modal:

```html
    <!-- modal -->
    <div class="modal fade" tabindex="-1" role="dialog" id="modalSubscription">
        <div class="modal-dialog" role="document" style="margin-top: 0">
            <div class="modal-content" style="border-radius: 0;">
                <div class="modal-header">
                    <h4 class="modal-title">Hola!</h4>
                </div>
                <div class="modal-body">
                    <p style="font-size: 16px; line-height: 1.6;">
                        ¿Quieres recibir notificaciones con ofertas comerciales sobre los productos que más te interesen?
                    </p>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-default" data-dismiss="modal">
                        No, gracias
                    </button>
                    <a href="#" data-dismiss="modal" type="button" class="btn btn-primary">Permitir</a>
                </div>
            </div>
        </div>
    </div>
    <!-- /.modal -->
```

```js
<script type="text/javascript">$('#modalSubscription').modal();</script>
```
