<script setup >
import {ref} from "vue"
const stuID =ref("");
const stuName = ref("");
</script>

<template>
  <h1>หน้าหลัก.  แบบฟอร์มลาออก</h1>
  <form>
  วันที่ <input type="date" name="" id="">
  คณะ
  <select name="" id="">
    <option>===กรุณาเลือกคณะ===</option>
    <option>คณะวิทยาศาสตร์</option>
    <option>คณะบริหาร</option>
    <option>คณะท่องเที่ยว</option>
    <option>คณะศิลปศาสตร์</option>
    <option>คณะสารสนเทศ</option>
    <option>คณะผลิตกรรมการเกษตร</option>
    <option>คณะพยาบาล</option>
    <option>คณะพืชไร่</option>
  </select>
  สาขา
  <select subject="">
    <option>===กรุณาเลือกสาขา===</option>
    <option>สาขาวิทยาศาสตร์</option>
    <option>สาขาบริหารธุรกิจ</option>
    <option>สาขาเทคโนโลยีการท่องเที่ยว</option>
    <option>สาขาศิลปะ</option>
    <option>สาขาเทคโนโลยีสารสนเทศ</option>
    <option>สาขาเทคโนโลยีการเกษตร</option>
    <option>คณะพยาบาล</option>
    <option>สาขาพืชไร่</option>
  </select>
    รหัสนศ. <input type="text" name="" id="" required>
    ชื่อ <input type="text" name="" id="" maxlength="100" required>
    หมายเลขโทรศัพท์ <input type="tel" neme="" id="" maxlength="10">
    <input type="submit" value="ยืนยันลาออก" />
  </form>
 {{ stuID }} {{ stuName }}
</template>

<style scoped></style>
