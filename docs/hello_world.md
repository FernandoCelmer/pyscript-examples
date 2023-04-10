> Test to see if it works with MkDocs :) I think it works!

<link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
<script defer src="https://pyscript.net/latest/pyscript.js"></script>

<py-config>
    plugins = [
        "https://pyscript.net/latest/plugins/python/py_tutor.py"
    ]
</py-config>

<section class="pyscript">
    Hello world! <br />
    This is the current date and time, as computed by Python:
    <py-script>
        from datetime import datetime
        now = datetime.now()
        display(now.strftime("%m/%d/%Y, %H:%M:%S"))
    </py-script>
</section>