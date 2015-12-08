# Veronica--encrypt-decrypt
//Name: Veronica Ciliberto
//Date: December 7, 2015
//Period: 7
//Lab: Encryptable String
//I got help from:

public class EncryptableString
{
	private String line;
	private boolean isEncrypted;
	private String crypt;
	private String decrypt;

	public EncryptableString()
	{
		line = "";
		isEncrypted = false;
	}

	public EncryptableString(String str)
	{
		line = str;
		isEncrypted = false;
	}

	public void encrypt(int offset)
	{
		if (isEncrypted == false)
		{
			crypt = "";

			for (int v = 0; v < line.length(); v++)
			{
				char LetterC = line.charAt(v);
				int LetterA = (int) (LetterC);
				LetterA += offset;
				LetterC = (char) (LetterA);
				crypt = crypt + LetterC;
			}

			isEncrypted = true;
			System.out.print(crypt);
		}
	}

	public void decrypt(int offset)
	{
		if (isEncrypted == true);
		{
			decrypt = "";

			for (int v = 0; v < line.length(); v++)
			{
				char Letter
			}
		}
	}

	public String toString()
	{
		return line;
	}
}
