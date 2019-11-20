# FSI-18ITD

Generelle dokumenter og konfigurasjon relatert til Fagskolen Innlandet

## Linker

- [Canvas](https://finn.instructure.com/)
- [Link til ISO-filer - Må være på det interne skolenettet](http://128.39.174.4/local/dreamspark)
- [Excel formeloversettelse: Engelsk til norsk](/Excel)
- [Skolerute 2019-2020](/assets/Skolerute_2019-2020.pdf)
- [Link til Stian "LarsenJR" Larsen sin FSI side](https://fsi.larsenjr.no/)
- [Ekstra mediafiler (bøker osv.)](https://media.chipset.no/dl/FSI/)

## Ukenummer:
Ukenummer: <strong id="weeknumber"></strong>

## Timeplan

Litt usikkert:

[![18IT-D Timeplan](/assets/images/2019-11-20_jS8XiA.png)](/assets/images/2019-11-20_jS8XiA.png)

<script type="text/javascript">
    /**
     * Cheers mate: https://gist.github.com/IamSilviu/5899269#gistcomment-2773524
     */
    Date.prototype.getWeek = function() {
        const today = this;
        const firstDayOfYear = new Date(today.getFullYear(), 0, 1);
        const pastDaysOfYear = (today - firstDayOfYear) / 86400000;
        return Math.ceil((pastDaysOfYear + firstDayOfYear.getDay() + 1) / 7);
    };

    window.addEventListener('DOMContentLoaded', () => {
        const weekElement = document.getElementById('weeknumber');
        weekElement.textContent = (new Date()).getWeek();
    });
</script>