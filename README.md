Udemy課程練習  #button #click #input #v-model

1.點擊button時增減數值
### @click='add(x)' , @click='remove(x)'

2.v-model 雙向綁定 
v-model="name"  ,  v-model="lastname"

3. 顯示 name, lastname
<p>Your Name: {{ fullname }}</p>

4.當name, lastname 有一個為空字元 就不會顯示名稱
fullname() {
  if (this.name === "" || this.lastname === "") {
    return "";
  }
    return this.name + " " + this.lastname;
  },
}
