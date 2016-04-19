# Andoid Studio Live Templates
##Custom live templates that can ease your typing 

### How to import:
Copy AndoidViewBindings.xml to the directory of Android Studio
 <p><b>win7: </b> C:\Users\\\<username>\\\.AndroidStudio1.5\config\templates </p>
and restart Andoid Studio if already running.

### List of templates: [Logs](#logs), [Decalration of views](#declaration), [FindViewById](#fvbid)
#### - <a name="logs"></a> Logs
| lge  | Error log message |
--- | ---
template: | Log.e("$tag$","$msg$");
<p></p>

#### - <a name="declaration"></a> Decalration of views:

| ptxt  | Declaration private TextView |
--- | --- | ---
template: | private TextView $view$;
<p></p>
| pedt  | Declaration private EditText |
--- | --- | ---
template: | private EditText $view$;
<p></p>
| pbtn  | Declaration private Button |
--- | --- | ---
template: | private Button $view$;
<p></p>
| pimb  | Declaration private ImageButton |
--- | --- | ---
template: | private ImageButton $view$;
<p></p>
| pimg  | Declaration private ImageView |
--- | --- | ---
template: | private ImageView $view$;
<p></p>
| prad  | Declaration private RadioButton |
--- | --- | ---
template: | private RadioButton $view$;
<p></p>
| pcb  | Declaration private CheckBox |
--- | --- | ---
template: | private CheckBox $view$;
<p></p>
| pspn  | Declaration private Spinner |
--- | --- | ---
template: | private Spinner $view$;
<p></p>
| precv  | Declaration private RecyclerView support.v7 |
--- | --- | ---
template: | private RecyclerView $view$;
<p></p>
| mostv  | Decalration of most used views |
--- | --- | ---
template: | the whole code below 
```
private TextView $txtView$; 

private EditText $edtView$; 

private Button $button$; 

private ImageButton $imgBtn$; 

private ImageView $imgView$;

private RadioButton $radioBtn$; 

private CheckBox $chBox$; 

private Spinner $spinner$; 

private RecyclerView $recView$;
```
<p></p>

#### - <a name="fvbid"></a> FindViewById:

| txt  | TextVIew findViewById with cast |
--- | --- | ---
template: | $view$ = (TextView) findViewById(R.id.$resId$);
<p></p>
| edt  | EditText findViewById with cast |
--- | --- | ---
template: | $view$ = (EditText) findViewById(R.id.$resId$);
<p></p>
| btn  | Button findViewById with cast |
--- | --- | ---
template: | $view$ = (Button) findViewById(R.id.$resId$);
<p></p>
| imb  | ImageButton findViewById with cast |
--- | --- | ---
template: | $view$ = (ImageButton) findViewById(R.id.$resId$);
<p></p>
| img  | ImageView findViewById with cast |
--- | --- | ---
template: | $view$ = (ImageView) findViewById(R.id.$resId$);
<p></p>
| rad  | RadioButton findViewById with cast |
--- | --- | ---
template: | $view$ = (RadioButton) findViewById(R.id.$resId$);
<p></p>
| cb  | CheckBox findViewById with cast |
--- | --- | ---
template: | $view$ = (CheckBox) findViewById(R.id.$resId$);
<p></p>
| spn  | Spinner findViewById with cast |
--- | --- | ---
template: | $view$ = (Spinner) findViewById(R.id.$resId$);
<p></p>
| recv  | RecyclerView findViewById with cast support.v7 |
--- | --- | ---
template: | $view$ = (RecyclerView) findViewById(R.id.$resId$);
<p></p>

#### Add/Edit/Remove
You can modify templates in File->Settings->Editor->Live Templates->AndoidViewBindings