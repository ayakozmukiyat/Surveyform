<!DOCTYPE html>
<html>
<body>
<h1>Медицинская история </h1>
<form action="/action_page.php">
  <label for="fname">Полное имя: <span style="color:red">*</span> </label><br>
  <input type="text"  value="">
  <input type="text"  value=""><br><br>

  <label for="fname">Номер телефона: <span style="color:red">*</span></label><br>
  <input type="number"  value=""> <br>

  <p>Check the conditions that apply to you or to any members of your immediate relatives:<span style="color:red">*</span><br></p>

  <input type="checkbox" id="Asthma" name="Asthma" required>
  <label for="vehicle1"> Asthma</label><br>
  <input type="checkbox" id="Cancer" name="Cancer" required>
  <label for="vehicle2"> Cancer</label><br>
  <input type="checkbox" id="Cardiac disease" name="Cardiac disease" required>
  <label for="vehicle3"> Cardiac disease</label><br>
  <input type="checkbox" id="Diabetes" name="Diabetes" required>
  <label for="vehicle3"> Diabetes</label><br>
  <input type="checkbox" id="Hypertension" name="Hypertension" required>
  <label for="vehicle3"> Hypertension</label><br>
  <input type="checkbox" id="Psychiatric disorder" name="Psychiatric disorder" required>
  <label for="vehicle3"> Psychiatric disorder</label><br>
  <input type="checkbox" id="Epilepsy" name="Epilepsy" required>
  <label for="vehicle3"> Epilepsy</label><br>

<p>Check the symptoms that you`re currently experiencing:<span style="color:red">*</span></p>
  <input type="checkbox" id="Chest pain" name="Chest pain" required>
  <label for="vehicle3"> Chest pain</label><br>
  <input type="checkbox" id="Respiratory" name="Respiratory" required>
  <label for="vehicle3"> Respiratory</label><br>
  <input type="checkbox" id="Cardiac disease" name="Cardiac disease" required>
  <label for="vehicle3"> Cardiac disease</label><br>
  <input type="checkbox" id="Cardiovascular" name="Cardiovascular" required>
  <label for="vehicle3"> Cardiovascular</label><br>
  <input type="checkbox" id="Hematological" name="Hematological" required>
  <label for="vehicle3"> Hematological</label><br>
  <input type="checkbox" id="Lymphatic" name="Lymphatic" required>
  <label for="vehicle3"> Lymphatic</label><br>
  <input type="checkbox" id="Neurological" name="Neurological" required>
  <label for="vehicle3"> Neurological</label><br>
  <input type="checkbox" id="Peychiatric" name="Peychiatric" required>
  <label for="vehicle3"> Peychiatric </label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" required>
  <label for="vehicle3"> Gastrointestinal</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" required>
  <label for="vehicle3"> Genitourinary</label><br>
  <input type="checkbox" id="Weight gain" name="Weight gain" required>
  <label for="vehicle3"> Weight gain </label><br>
  <input type="checkbox" id="Weightloss" name="Weightloss" required>
  <label for="vehicle3"> Weightloss</label><br>
  <input type="checkbox" id="Musculoskeletal" name="Musculoskeletal" required>
  <label for="vehicle3"> Musculoskeletal</label><br>

<p>Are you currently taking any medication? <span style="color:red">*</span></p>

  <form><input type="radio" id="Yes" name="Yes" required value="HTML">
  <label for="html">Да</label><br>
  <input type="radio" id="No" name="No" required value="HTML">
  <label for="html">Нет</label><br></form>

<p>Do you have any medication allergies?<span style="color:red">*</span> </p>
  <form><input type="radio" id="Yes" name="Yes" required value="HTML">
  <label for="html">Да</label><br>
  <input type="radio" id="Not" name="Not" required value="HTML">
  <label for="html">Нет</label><br>
  <input type="radio" id="Not sure" name="Not sure" required value="HTML">
  <label for="html">Not sure</label><br></form>

<p>What is your Gender? <span style="color:red">*</span></p>
  <form><input type="radio" id="Мужской" name="Мужской" required value="Man">
  <label for="html">Мужской</label><br>
  <input type="radio" id="Женский" name="Женский" required value="Women">
  <label for="html">Женский</label><br></form>

<p>Do you use or do you have history of using tobacco?<span style="color:red">*</span></p>
<form action="/action_page.php">
  <label for="using tobacco"></label>
  <select id="using tobacco" name="using tobacco">
    <option value="Please select">Please select</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>
  <input type="submit">
</form>

<p>Do you use or do you have history of using illegal drugs?<span style="color:red">*</span> </p>

<form action="/action_page.php">
  <label for="illegal drugs"></label>
  <select id="illegal drugs" name="illegal drugs">
    <option value="Please select">Please select</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>
  <input type="submit">
</form>

<p>How often do you consume alcohol? <span style="color:red">*</span></p>
<form>  <input type="radio" id="Ежедневно" name="Ежедневно" value="">
  <label for="html">Ежедневно</label>
  <input type="radio" id="Еженедельно" name="Еженедельно" value="">
  <label for="html">Еженедельно</label>
  <input type="radio" id="Ежемесячно" name="Ежемесячно" value="">
  <label for="html">Ежемесячно</label><br>
  <input type="radio" id="Occasionally" name="Occasionally" value="">
  <label for="html">Occasionally</label>
  <input type="radio" id="Никогда" name="Никогда" value="">
  <label for="html">Никогда</label><br>
  <br><input type="submit" value="Отправить">
</form>


</form>
</body>
</html>
