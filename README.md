# stiki.ac.id

database stiki_terpadu example data

more data 
contact : nuledsec@proton.me

```
INSERT INTO `tb_akd_rf_mahasiswa` VALUES ('22TEST001', 'TI-S1', 'R', NULL, '2022', 'Ganjil', 'Baru', '20222', 'TEST MAHASISWA', NULL, NULL, NULL, NULL, NULL, 'Malang', NULL, 'L', NULL, NULL, '2022-11-14', NULL, '020195', NULL, NULL, 'A', NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, '111', NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, 'YES', 'YES', NULL, NULL, NULL, NULL, 'SAKTI', 'afis@stiki.ac.id', '2022-11-14 13:45:07', 'by-trigger', '2022-11-14 13:52:10');
INSERT INTO `tb_akd_rf_mahasiswa` VALUES ('999999', 'TI-S1', 'R', '2023-02-08', '2023', 'Ganjil', 'Baru', '20293', 'NI HAO WO SHI SISFO', '564652549856', 'jl lorem RT 1 RW 1 lorem lorem Kode Pos 666', 'Kota Jeddah', 521, 'Jalan jl lorem RT 1 RW 1 lorem lorem ,Kode Pos 666 lorem', 'Kota Jeddah', 521, 'P', 'Malang', 33, '2023-04-07', 2, NULL, NULL, '36619', 'MB', NULL, NULL, NULL, NULL, '082228466500', '082228466500', '999999@mhs.stiki.ac.id', 'art.thea0@gmail.com', '056173', '2313', 'BAPAK', '3244324324', 'IBU', '431421321321', 'Jalan jl lorem RT 1 RW 1 lorem lorem ,Kode Pos 666 lorem', '521', 36, 15, '23131', '313231', NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, 'NO', 2426, 'PMB', 'afis@stiki.ac.id', '2023-02-08 11:05:23', NULL, NULL, NULL, 'by-trigger', '2023-02-21 08:21:12');
INSERT INTO `tb_akd_rf_mahasiswa` VALUES ('22113L001', 'TI-S1', 'M', '2023-03-14', '2023', 'Genap', 'Pindahan', '20233', 'MARK RAYMOND ROM', NULL, 'Mababanaba San Jose Tarlac', NULL, NULL, NULL, NULL, NULL, 'L', 'Meycauayan,Bulacan', NULL, '2023-03-07', 3, '010034', NULL, NULL, 'MB', NULL, NULL, NULL, NULL, '09501781071', '09501781071', '22113L001@mbkm.stiki.ac.id', 'mrom210143@tau.edu.ph', NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, 'db', 'adrian', '2023-03-13 16:23:00', NULL, NULL, NULL, 'by-trigger', '2023-03-14 08:52:38');
INSERT INTO `tb_akd_rf_mahasiswa` VALUES ('22113L001', 'TI-S1', 'M', '2023-03-14', '2023', 'Genap', 'Pindahan', '20233', 'MARK RAYMOND ROM', NULL, 'Mababanaba San Jose Tarlac', NULL, NULL, NULL, NULL, NULL, 'L', 'Meycauayan,Bulacan', NULL, '2023-03-07', 3, '010034', NULL, NULL, 'MB', NULL, NULL, NULL, NULL, '09501781071', '09501781071', '22113L001@mbkm.stiki.ac.id', 'mrom210143@tau.edu.ph', NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, 'db', 'adrian', '2023-03-13 16:23:00', NULL, NULL, NULL, 'by-trigger', '2023-03-14 08:54:59');
INSERT INTO `tb_akd_rf_mahasiswa` VALUES ('22113L001', 'TI-S1', 'M', '2023-03-14', '2023', 'Genap', 'Pindahan', '20233', 'MARK RAYMOND ROM', NULL, 'Mababanaba San Jose Tarlac', NULL, NULL, NULL, NULL, NULL, 'L', 'Meycauayan,Bulacan', NULL, '2023-03-07', 3, '010034', NULL, NULL, 'MB', NULL, NULL, NULL, NULL, '09501781071', '09501781071', '22113L001@mbkm.stiki.ac.id', 'mrom210143@tau.edu.ph', NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, 'db', 'adrian', '2023-03-13 16:23:00', NULL, NULL, NULL, 'by-trigger', '2023-03-14 08:57:31');
INSERT INTO `tb_akd_rf_mahasiswa` VALUES ('23211L006', 'DK-S1', 'M', '2023-03-14', '2023', 'Genap', 'Pindahan', '20233', 'DEVA AMIRTHA PRIYA R', NULL, '42/24 KANNABIRAN KOVIL STREET, EASSA PALLAVARAM', NULL, NULL, NULL, NULL, NULL, 'P', 'INDIA, KANCHIPURAM', NULL, '2003-09-22', 4, '010034', NULL, NULL, 'MB', NULL, NULL, NULL, NULL, '8825792053', '8825792053', '23211L006@mbkm.stiki.ac.id', 'divyadap2293@gmail.com ', NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, 'YES', NULL, 'db', 'adrian', '2023-03-13 16:23:00', NULL, NULL, NULL, 'by-trigger', '2023-03-14 10:22:45');

-- ----------------------------
-- Table structure for tb_akd_tr_ambil_mk
-- ----------------------------
DROP TABLE IF EXISTS `tb_akd_tr_ambil_mk`;
CREATE TABLE `tb_akd_tr_ambil_mk`  (
  `Kd_Perwalian` varchar(10) CHARACTER SET utf8 COLLATE utf8_general_ci NOT NULL DEFAULT '',
  `Kode_MK` varchar(10) CHARACTER SET utf8 COLLATE utf8_general_ci NOT NULL DEFAULT '',
  `Tahun` varchar(4) CHARACTER SET utf8 COLLATE utf8_general_ci NOT NULL DEFAULT '',
  `kelas` varchar(3) CHARACTER SET utf8 COLLATE utf8_general_ci NULL DEFAULT '',
  `Pengambilan_Ke` int(2) NULL DEFAULT NULL,
  `Periode_Sem` enum('Ganjil','Genap','Pendek_Ganjil','Pendek_Genap','1_prf','2_prf','3_prf') CHARACTER SET utf8 COLLATE utf8_general_ci NOT NULL DEFAULT 'Ganjil',
  `isCanChange` enum('YES','NO') CHARACTER SET utf8 COLLATE utf8_general_ci NULL DEFAULT NULL,
  `Kode_DropMK` varchar(10) CHARACTER SET utf8 COLLATE utf8_general_ci NULL DEFAULT NULL,
  `Created_App` varchar(25) CHARACTER SET utf8 COLLATE utf8_general_ci NULL DEFAULT NULL,
  `Created_By` varchar(100) CHARACTER SET utf8 COLLATE utf8_general_ci NULL DEFAULT NULL,
  `Created_Date` datetime NULL DEFAULT NULL,
  `Modified_App` varchar(25) CHARACTER SET utf8 COLLATE utf8_general_ci NULL DEFAULT NULL,
  `Modified_By` varchar(100) CHARACTER SET utf8 COLLATE utf8_general_ci NULL DEFAULT NULL,
  `Modified_Date` datetime NULL DEFAULT NULL,
  `Trashed_By` varchar(100) CHARACTER SET utf8 COLLATE utf8_general_ci NULL DEFAULT NULL,
  `Trashed_Date` datetime NULL DEFAULT NULL
) ENGINE = InnoDB CHARACTER SET = utf8 COLLATE = utf8_general_ci ROW_FORMAT = Dynamic;

-- ----------------------------
-- Records of tb_akd_tr_ambil_mk
-- ----------------------------
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201810711', 'TI14BB11', '2018', 'B', 1, 'Ganjil', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2018-09-07 10:32:04', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201810711', 'TI14KK12', '2018', 'B1', 1, 'Ganjil', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2018-09-07 10:32:04', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201810711', 'TI14KK13', '2018', 'B', 1, 'Ganjil', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2018-09-07 10:32:04', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201810711', 'TI14KK14', '2018', 'B', 1, 'Ganjil', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2018-09-07 10:32:04', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201810711', 'TI14KK22', '2018', 'B', 1, 'Ganjil', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2018-09-07 10:32:04', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201810711', 'TI14PK11', '2018', 'B1', 1, 'Ganjil', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2018-09-07 10:32:04', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201830253', 'TI14KB21', '2018', 'B', 1, 'Genap', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2019-02-19 16:45:38', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201830253', 'TI14KB22', '2018', 'B1', 1, 'Genap', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2019-02-19 16:36:09', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201830253', 'TI14KB23', '2018', 'B1', 1, 'Genap', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2019-02-19 16:36:09', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201830253', 'TI14KB24', '2018', 'B1', 1, 'Genap', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2019-02-19 16:36:09', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201830253', 'TI14KK11', '2018', 'B', 1, 'Genap', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2019-02-19 16:45:38', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201830253', 'TI14KK21', '2018', 'B', 1, 'Genap', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2019-02-19 16:45:38', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
[/code]
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201830253', 'TI14KK23', '2018', 'B', 1, 'Genap', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2019-02-19 16:45:38', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201830253', 'TI14KK24', '2018', 'B', 1, 'Genap', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2019-02-19 16:45:38', NULL, NULL, NULL, 'adrian', '2019-03-19 11:21:29');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201810676', 'TI14BB11', '2018', 'A', 1, 'Ganjil', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2018-09-07 10:19:03', NULL, NULL, NULL, 'adrian', '2019-03-19 11:22:12');
INSERT INTO `tb_akd_tr_ambil_mk` VALUES ('201810676', 'TI14KK12', '2018', 'A1', 1, 'Ganjil', 'NO', NULL, 'SIAKAD', 'dedyari@stiki.ac.id', '2018-09-07 10:19:03', NULL, NULL, NULL, 'adrian', '2019-03-19 11:22:12');
```
