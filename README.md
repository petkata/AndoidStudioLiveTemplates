# Andoid Studio Live Templates
##Custom live templates that can ease your typing 

### How to import:
Copy AndoidViewBindings.xml to the directory of Android Studio
 <b>win7: </b> C:\Users\<username>\.AndroidStudio1.5\config\templates
and restart Andoid Studio if already running.

### List of templates:
#### Logs
| lge  | Error log message |
Log.e("$tag$","$msg$");
<p></p>

#### FindViewById:

| txt  | TextVIew findViewById with cast |
$view$ = (TextView) findViewById(R.id.$resId$);
<p></p>
| edt  | EditText findViewById with cast |
$view$ = (EditText) findViewById(R.id.$resId$);
<p></p>
| btn  | Button findViewById with cast |
$view$ = (Button) findViewById(R.id.$resId$);
<p></p>
| imb  | ImageButton findViewById with cast |
$view$ = (ImageButton) findViewById(R.id.$resId$);
<p></p>
| img  | ImageView findViewById with cast |
$view$ = (ImageView) findViewById(R.id.$resId$);
<p></p>
| rad  | RadioButton findViewById with cast |
$view$ = (RadioButton) findViewById(R.id.$resId$);
<p></p>
| cb  | CheckBox findViewById with cast |
$view$ = (CheckBox) findViewById(R.id.$resId$);
<p></p>
| spn  | Spinner findViewById with cast |
$view$ = (Spinner) findViewById(R.id.$resId$);
<p></p>
| recv  | RecyclerView findViewById with cast support.v7 |
$view$ = (RecyclerView) findViewById(R.id.$resId$);
<p></p>

#### Decalration of views:

| ptxt  | Declaration private TextView |
private TextView $view$;
<p></p>
| pedt  | Declaration private EditText |
private EditText $view$;
<p></p>
| pbtn  | Declaration private Button |
private Button $view$;
<p></p>
| pimb  | Declaration private ImageButton |
private ImageButton $view$;
<p></p>
| pimg  | Declaration private ImageView |
private ImageView $view$;
<p></p>
| prad  | Declaration private RadioButton |
private RadioButton $view$;
<p></p>
| pcb  | Declaration private CheckBox |
private CheckBox $view$;
<p></p>
| pspn  | Declaration private Spinner |
private Spinner $view$;
<p></p>
| precv  | Declaration private RecyclerView support.v7 |
private RecyclerView $view$;
<p></p>
| mostv  | Decalration of most used views |
private TextView $txtView$;
private EditText $edtView$;
private Button $button$;
private ImageButton $imgBtn$;
private ImageView $imgView$;
private RadioButton $radioBtn$;
private CheckBox $chBox$;
private Spinner $spinner$;
private RecyclerView $recView$;
<p></p>

#### Add/Edit/Remove
You can modify templates in File->Settings->Editor->Live Templates->AndoidViewBindings