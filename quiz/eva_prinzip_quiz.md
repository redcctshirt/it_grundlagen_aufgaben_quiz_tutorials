# EVA-Prinzip - Quiz

{% regexp %}
Was bedeutet die Abkürzung EVA (EVA-Prinzip - Grundschema der Datenverarbeitung) ?
{% solution %}
Eingabe Verarbeitung Ausgabe
{% validation %}
/(\s*Eingabe[\s,]*Verarbeitung[\s,]*Ausgabe\s*)/i
{% editor %}
Hier bitte die Lösung eintippen.
{% endregexp %}

<quiz name="">
    <question multiple>
        <p>Welche Hardwareelemente kümmern sich um die Ausgabe in der Datenverarbeitung ?</p>
        <answer correct>Drucker</answer>
        <answer>Tastatur</answer>
        <answer correct>Bildschirm</answer>
        <answer correct>Plotter</answer>
        <answer>CPU</answer>
        <explanation></explanation>
    </question>
    <question>
        <p>Welches Gerät gehört nicht zum Teil der Eingabe in der Datenverarbeitung ?</p>
        <answer>Tastatur</answer>
        <answer>Maus</answer>
        <answer correct>Beamer</answer>
        <answer>Scanner</answer>
    </question>
</quiz>

{% regexp %}
Bei welchem Gerät sind Ein- und Ausgabe (Datenverarbeitung) nur schwer zu trennen ?
{% solution %}
Smartphone
{% validation %}
/(\s*Smartphone\s*)|(\s*Handy\s*)|(\s*Mobiltelefon\s*)|(\s*Touchscreen\s*)|(\s*Tablet\s*)|(\s*Tabletcomputer\s*)/i
{% editor %}
Hier bitte die Lösung eintippen.
{% endregexp %}
