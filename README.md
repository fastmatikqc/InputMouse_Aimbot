#### put this into ur main
	if (!librarys::init())
	{
		printf("The librarys was not initialized");
		Sleep(3000);
		exit(0);
	}
	if (!input::init())
	{
		printf("The input was not initialized");
		Sleep(3000);
		exit(0);
	}
