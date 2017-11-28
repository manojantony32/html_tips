--Bootstrap like column base view for basic html--

<div class="Row">
    <div class="Column">welcome hello <br/> testing system</div>
    <div class="Column">welcome hello</div>
    <div class="Column">welcome hello testing</div>
</div>

.Row
{
    display: table;
    width: 100%;
    table-layout: fixed;
    border-spacing: 10px;
}
.Column
{
    display: table-cell;
    background-color: red;
}
