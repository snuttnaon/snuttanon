# snuttanon

contract BetterFarmer {

    address creator;

    struct farmer {
        address id;
        string name;
        string gender;
        string province;
    }
    mapping(address => farmer) public allFarmer;

    struct activity {
        address id;
        string activityType;
        string description;
        uint amount;
    }
    mapping(address => activity[]) public stories;

}
