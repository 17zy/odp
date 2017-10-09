# ODP
    ODP is the 17zuoye's open data platform.
  
        数据文件每天产生两个，一个是老师数据文件，一个是学生数据文件。老师的数据文件命名方式为gdm_tea_process_detail_YYYYMMDD.zip，
    学生文件的命名方式为gdm_stud_process_detail_YYYYMMDD.zip。数据文件中，每行为一条数据，包含老师布置作业，学生做作业的各个维度信息，
    包括地区、班级、作业、知识点、做题结果和做题时间等等。 
        为了保护个人隐私，这些信息都做了hash。通过这些唯一的hash值，可以得到同一份作业、同一道题或者同一个知识点在不同老师、学生
    群体里的各种集合数据，对于研究分类算法，题目、知识点相关性，做题对错、做题时间和知识点掌握的对应关系等方向会有一定的帮助。
    
# 数据格式定义

TABLE_NAME: STUD_PROCESS_DETAIL(学生做题详细)：
student_id	学生ID
school_id	学校ID
grade	    年级
group_id	班组ID
homework_id	作业ID
subject	    学科
question_id	题目ID
facility	题目难易度
kp_id	    题目相关知识点
is_right	是否回答正确
duration	做题时长
school_level学段


TABLE_NAME：TEA_PROCESS_DETAIL(老师布置作业详细)：
col_name	注释
teacher_id	老师ID
region_id	老师地区ID
school_id	学校ID
grade	    年级
group_id	班组ID
homework_id	作业ID
subject	    学科
question_id	题目ID
kp_id	    题目相关知识点
school_level学段

# 下载地址
  中国大陆机构下载地址 ： http://101.251.244.26/download_api/   
  境外机构下载地址 ：http://164.52.12.42/download_api/ 
    
    
    
    
  
