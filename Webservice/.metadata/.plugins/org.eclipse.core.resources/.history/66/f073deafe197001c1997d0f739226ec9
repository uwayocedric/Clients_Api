package com.service;

import javax.persistence.Column;
import javax.persistence.Entity;
import javax.persistence.GeneratedValue;
import javax.persistence.GenerationType;
import javax.persistence.Id;
import javax.xml.bind.annotation.XmlRootElement;


@XmlRootElement
@Entity(name="Clients")
public class Clients {

	@Id
	@GeneratedValue(strategy = GenerationType.IDENTITY)
	@Column(name="S_ROWID")
	int S_ROWID;
	@Column(name="ACL")
	String ACL;
	@Column(name="ACCUNTNUMBER")
	String ACCUNTNUMBER;
	@Column(name="ACCOUNTNAME")
	String ACCOUNTNAME;
	@Column(name="FIRSTNAME")
	String FIRSTNAME;
	@Column(name="LASTNAME")
	String LASTNAME;
	@Column(name="BRANCHCODE")
	String BRANCHCODE;
	
	public Clients() {
	}
	
	public Clients(String ACL, int s_ROWID, String ACCUNTNUMBER, String ACCOUNTNAME, String FIRSTNAME, String LASTNAME, String BRANCHCODE) {
		// TODO Auto-generated constructor stub
	}
	public String getACL() {
		return ACL;
	}
	public void setACL(String aCL) {
		ACL = aCL;
	}
	public int getS_ROWID() {
		return S_ROWID;
	}
	public void setS_ROWID(int s_ROWID) {
		S_ROWID = s_ROWID;
	}
	public String getACCUNTNUMBER() {
		return ACCUNTNUMBER;
	}
	public void setACCUNTNUMBER(String aCCUNTNUMBER) {
		ACCUNTNUMBER = aCCUNTNUMBER;
	}
	public String getACCOUNTNAME() {
		return ACCOUNTNAME;
	}
	public void setACCOUNTNAME(String aCCOUNTNAME) {
		ACCOUNTNAME = aCCOUNTNAME;
	}
	public String getFIRSTNAME() {
		return FIRSTNAME;
	}
	public void setFIRSTNAME(String fIRSTNAME) {
		FIRSTNAME = fIRSTNAME;
	}
	public String getLASTNAME() {
		return LASTNAME;
	}
	public void setLASTNAME(String lASTNAME) {
		LASTNAME = lASTNAME;
	}
	public String getBRANCHCODE() {
		return BRANCHCODE;
	}
	public void setBRANCHCODE(String bRANCHCODE) {
		BRANCHCODE = bRANCHCODE;
	}
	
	
}