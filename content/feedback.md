---
title: Обратная связь
---

These are all the built-in link styles available in Lynx. Don't forget that you can also create your own styles --- check the [readme](https://github.com/jpanther/lynx/blob/stable/README.md) for more details.
<br><br>

{{< rawhtml >}}
<link rel="stylesheet" href="/css/form.css">
<script type="text/javascript">var submitted=false;</script>
<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" 
onload="if(submitted) {window.location='/thankyou';}"></iframe>

<form action="https://docs.google.com/forms/d/e/1FAIpQLScvH7c2oDa9ksNClTZOPCTGgzShJ7fzPA0KiV_uUic_frGcRg/formResponse" 
method="post" target="hidden_iframe" onsubmit="submitted=true;">
</form>
<form action="https://docs.google.com/forms/d/e/1FAIpQLScvH7c2oDa9ksNClTZOPCTGgzShJ7fzPA0KiV_uUic_frGcRg/formResponse" method="post" target="hidden_iframe" onsubmit="submitted=true">
  <label>Ваше имя:</label>
        <input type="text" placeholder="Введите ваше имя" class="form-input" name="entry.2005620554" required>

  <label>Email:</label>
        <input type="email" placeholder="Введите ваш Email адрес" class="form-input" name="entry.1045781291" required>

   <label>Тема сообщения:</label>
        <select name="entry.1065046570" id="topics" class="form-input" required>
          <option value="Вопрос о товаре">Вопрос о товаре</option>
          <option value="Помощь с установкой ПО">Помощь с установкой ПО</option>
          <option value="Сообщить о проблеме">Сообщить о проблеме</option>
          <option value="Другое">Другое</option>
        </select>
  
        <!--<input type="text" placeholder="Укажите тему сообщения" class="form-input" name="entry.1065046570">-->

   <label>Сообщение:</label>
        <textarea rows="5" placeholder="Введите текст сообщения" class="form-input" name="entry.839337160" required></textarea>

   <button type="submit">Отправить</button>
</form>
{{< /rawhtml >}}

